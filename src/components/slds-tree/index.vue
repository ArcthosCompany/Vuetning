<template>
    <div class="slds-tree_container">
        <h4 id="treeheading" class="slds-tree__group-header">
            {{ header }}
        </h4>
        <ul aria-labelledby="treeheading" class="slds-tree" role="tree">
            <slds-tree-node v-for="(child, index) in tree.children" :key="child.label + '' + index + '' + 1" :node="child" parent="root" :level="1"/>
        </ul>
    </div>
</template>

<script>
    import SldsTreeNode from './slds-tree-node'
    export default {
        name: 'SldsTree',
        components:{
            SldsTreeNode
        },
        props: {
            tree: Object,
            header: String
        }
    }
</script>

<style scoped>
</style>
