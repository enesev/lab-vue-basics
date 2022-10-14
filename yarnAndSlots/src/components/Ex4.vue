<!-- Iteration 4 | Display a list of elements that are stored inside a component

Remember how hard for loops seemed with vanilla JavaScript? Vue does a lot of the heavy lifting when we're using them, and can allow us to display a list of elements on the screen in a much easier way.

In this exercise, you're going to practice how to use the v-for directive. The challenge has the following components:

    You need to create a list of posts inside the data of one of your Vue components. These posts need to include the following data: title, description, and content; and you need at least three of them.
    Then, you have to make the posts "show up" on your template using the v-for directive.

Again, if you're stuck here, you can always refer to the official documentation. -->

<template>
    <!-- nombredeLaVariable  -->
        <div v-for="element in data">
            {{element.title}} , {{element.description}} , {{element.content}}
    
        </div>
        
    </template>
    <script setup>
     const data = [
        {
            title: 'Titulo 1',
            description: 'Description 1' ,
            content: 'Contenido1'
    
        },
        {
            title: 'Titulo 2',
            description:'Description 2',
            content: 'Contenido2'
    
        },
        {
            title: 'Titulo 3',
            description: 'Description 3',
            content: 'Contenido1'
    
        }
     ]
    
    
    </script>
    <style scoped>
    </style>