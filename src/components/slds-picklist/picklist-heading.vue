<template>
    <slds-dropdown-heading :heading="heading"/>
</template>

<script>
import SldsDropdownHeading from "@/components/slds-options/dropdown-heading";

export default {
    name: "SldsPicklistHeading",

    components: {
        SldsDropdownHeading
    },

    props: {
        heading: {type: String, required: true}
    }
}
</script>
