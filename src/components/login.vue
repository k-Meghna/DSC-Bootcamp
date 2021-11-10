<template lang="">
    <div>
        <h1> login Component </h1>
       <h3> {{ name }} </h3>
       <button> sign in {{name}} {{btntext}} </button> 
       
    </div>
</template>
<script>

export default {
 name: 'login',
 props:['name','btntext']

}
</script>