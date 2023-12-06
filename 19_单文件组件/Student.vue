<template></template>

<script>
// 定义student组件
export default {
    name: 'Student',
    template: `
        <div>
            <h2>姓名：{{name}}</h2>    
            <h2>年龄：{{age}}</h2>    
        </div>
        `,
    data() {
        return {
            name: '张三',
            address: '18'
        }
    }
}
</script>