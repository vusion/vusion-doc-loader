<template>
<s-materials-view type="components" :groups="groups"></s-materials-view>
</template>

<script>
export default {
    data() {
        return { groups: this.$docs.componentsGroups };
    },
};
</script>
