<template>
    <li :aria-level="level" :aria-expanded="expandedData" role="treeitem" :aria-label="node.label" tabindex="0">
        <div class="slds-tree__item" @click="onClickTreeItem">
            <slds-button-icon icon="utility:chevronright" class="slds-m-right_x-small" :class="{'slds-is-disabled': !hasChildren}" aria-hidden="true" tabindex="-1"/>
            <span class="slds-has-flexi-truncate">
                <span class="slds-tree__item-label slds-truncate" title="Tree Item">{{ node.label }}</span>
            </span>
        </div>
        <ul v-if="hasChildren && expandedData" role="group">
            <slds-tree-node v-for="(child, index) in node.children" :key="child.label + '' + index + '' + level" :node="child" :parent="node.label" :level="level + 1"/>
        </ul>
    </li>
</template>

<script>
import SldsButtonIcon from '../slds-button-icon/index.vue'
export default {
    name: 'SldsTreeNode',
    components:{
        SldsButtonIcon
    },
    props:{
        node: {
            label: String,
            children: Array,
        },
        parent:{
            label: String,
            required: true,
        },
        level: {
            type: Number,
            required: true
        },
        expanded: {
            type: Boolean,
            default: false
        }
    },
    data(){
        return {
            expandedData: this.expanded || false,
        }
    },
    computed:{
        hasChildren(){
            return this.node.children && this.node.children.length > 0;
        }
    },
    methods:{
        onClickTreeItem(){
            if(this.hasChildren){
                this.expandedData = !this.expandedData;
            }else{
                this.$emit('node', { label: this.node.label,  level: this.level, parent: this.parent })
            }
        }
    }
}
</script>

<style>

</style>