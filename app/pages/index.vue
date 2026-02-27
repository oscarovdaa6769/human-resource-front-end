
  <template>
  <div class="banner container py-10 h-100 ">
   <h1>Job listing</h1>
   <div v-for="data in jobPostingdatas">
        {{ data.Description }}
   </div>
 
  </div>
</template>



<script setup >
import axios from 'axios'


const config = {
  headers: {
    Authorization: 'Bearer 88d3aad4ff049f949573e2071b029b303573ae1b8be8c0707cdb7afde5cb38543ac9c807a9f87c0d750394313a365a8b2c7527d2ca129b379a347f1c90020d28f517b6407d86cf84499171c5e1302e204f6633a815a5518e91ed7b097f8256c776ad51c0b5033ed281198e403c0ee922441449184b1311e29eb7afd5e3f6f76e'
  }
};

const dataFetch = await axios.get('http://localhost:1337/api/job-postings?populate*', config);
const jobPostingDatas = dataFetch.data.data;

console.log(jobPostingDatas);
</script>


