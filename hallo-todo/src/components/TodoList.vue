<template>
     <div>
          <ul>
               <li v-for="todoElement in todoElemente" :key="todoElement.id" :class="{ 'fertig' : todoElement.is_done }">
                    <input type="checkbox" v-model="todoElement.is_done">
                    {{todoElement.title}}
               </li>
          </ul>
     </div>
</template>

<script>
export default {
     data: () => ({
          todoElemente: [
               {
                    "id": 1,
                    "title": "Vue JS Tutorial durcharbeiten",
                    "is_done": true
               },
               {
                    "id": 2,
                    "title": "Den Vue JS Kurs auf codercampus.de kaufen",
                    "is_done": false
               },
               {
                    "id": 3,
                    "title": "Vue JS beherrschen",
                    "is_done": true
               },
          ]
     })
}
</script>

<style>
.fertig { text-decoration: line-through; }
</style>