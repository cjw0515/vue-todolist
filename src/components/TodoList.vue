<template>
    <section>        
        <!-- <transition-group name="list" tag="ul">          -->
        <ul>
            <li class="shadow">
                <i class="checkBtn fas fa-check" aria-hidden="true"></i>  
                룰루루루룰ㄹ              
                <span class="removeBtn" type="button">
                    <i class="far fa-trash-alt" aria-hidden="true"></i>
                </span>    
            </li>
        </ul> 
        <!-- </transition-group> -->
    </section>    
</template>

<script>
export default {    

}
</script>

<style scoped>
ul {
  list-style-type: none;
  padding-left: 0px;
  margin-top: 0;
  text-align: left;
}
li {
  display: flex;
  min-height: 50px;
  line-height: 50px;
  margin: 0.5rem 0;
  padding: 0 0.9rem;
  background: white;
  border-radius: 5px;
}

.checkBtn {
  line-height: 45px;
  color: #62acde;
  margin-right: 5px;
}

.removeBtn {
  margin-left: auto;
  color: #de4343;
}
</style>
<style scoped>
.list-enter-active,
.list-leave-active {
  transition: all 1s;
}
.list-enter,
.list-leave-to {
  opacity: 0;
  transform: translateY(30px);
}
</style>

