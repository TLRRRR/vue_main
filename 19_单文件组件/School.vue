<template></template>

<script>
// 定义school组件
export default {
    name: 'School',
    template: `
        <div>
            <h2>学校：{{name}}</h2>    
            <h2>地址：{{address}}</h2>    
        </div>
        `,
    data() {
        return {
            name: '台东小学',
            address: '台东'
        }
    }
}
</script>