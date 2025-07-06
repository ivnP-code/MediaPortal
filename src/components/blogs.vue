<template>
      <div class="publics">ПОСЛЕДНИЕ ПУБЛИКАЦИИ</div>
       <div class="allpacks">

<div class="pack">
  <div class="image-wrapper">
    <img src="/public/images/humans.jpg" class="inboxpic">
  </div>
  <div class="inboxcapital">Lorem ipsum dolor sit amet.</div>
  <div class="inboxtext">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Officiis tempore molestias porro a, incidunt quam ex esse magni itaque minus tempora, hic dolorem dicta placeat recusandae repellendus ad suscipit in.</div>
  <button class="more">ДАЛЕЕ</button>
</div>    
<div class="pack">
  <div class="image-wrapper">
    <img src="/images/stockjpg.jpg" class="inboxpic">
  </div>
  <div class="inboxcapital">Lorem ipsum dolor sit amet.</div>
  <div class="inboxtext">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Officiis tempore molestias porro a, incidunt quam ex esse magni itaque minus tempora, hic dolorem dicta placeat recusandae repellendus ad suscipit in.</div>
  <button class="more">ДАЛЕЕ</button>
</div> <div class="pack">
  <div class="image-wrapper">
    <img src="/images/Android_vector.jpg" class="inboxpic">
  </div>
  <div class="inboxcapital">Lorem ipsum dolor sit amet.</div>
  <div class="inboxtext">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Officiis tempore molestias porro a, incidunt quam ex esse magni itaque minus tempora, hic dolorem dicta placeat recusandae repellendus ad suscipit in.</div>
  <button class="more">ДАЛЕЕ</button>
</div> <div class="pack">
  <div class="image-wrapper">
    <img src="/images/face.jpg" class="inboxpic">
  </div>
  <div class="inboxcapital">Lorem ipsum dolor sit amet.</div>
  <div class="inboxtext">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Officiis tempore molestias porro a, incidunt quam ex esse magni itaque minus tempora, hic dolorem dicta placeat recusandae repellendus ad suscipit in.</div>
  <button class="more">ДАЛЕЕ</button>
</div> 
<div class="pack">
  <div class="image-wrapper">
    <img src="/images/Cat03.jpg" class="inboxpic">
  </div>
  <div class="inboxcapital">Lorem ipsum dolor sit amet.</div>
  <div class="inboxtext">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Officiis tempore molestias porro a, incidunt quam ex esse magni itaque minus tempora, hic dolorem dicta placeat recusandae repellendus ad suscipit in.</div>
  <button class="more">ДАЛЕЕ</button>
</div> <div class="pack">
  <div class="image-wrapper">
    <img src="/images/convert_to_jpg.png" class="inboxpic">
  </div>
  <div class="inboxcapital">Lorem ipsum dolor sit amet.</div>
  <div class="inboxtext">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Officiis tempore molestias porro a, incidunt quam ex esse magni itaque minus tempora, hic dolorem dicta placeat recusandae repellendus ad suscipit in.</div>
  <button class="more">ДАЛЕЕ</button>
</div> 
      </div>
</template>

<style scoped>
.inboxcapital{
      font-size: 24px;
      font-weight: 900;
}
.publics {
  padding-bottom: 20px;
  border-bottom: 4px solid rgb(22, 108, 206);
  font-weight: 700;
  font-size: 24px;
  margin-left: 80px;
  margin-right: 80px;
}

.allpacks {
  display: grid;
  grid-template-columns: repeat(2, 1fr); 
  gap: 20px;
  padding: 20px 80px;
}
.image-wrapper {
  overflow: hidden;
  display: flex;
  justify-content: center;
  align-items: center;
  max-width: 400px;
  margin: 0 auto;
}

.pack {
  position: relative;
  padding: 10px;
  border-radius: 12px;
  text-align: center;
  box-shadow: 0 2px 6px rgba(0,0,0,0.1);
}

.inboxpic{
width: auto;
height: 400px;
transition: transform 0.5s ease; 
}

.inboxpic:hover{
transform: scale(1.2);
}
.more{
 max-width: 100px;
border: solid rgb(92, 184, 214) 2px;
color: rgb(92, 184, 214);
font-weight: 700;
padding: 10px;
margin-top: 20px;
display: flex;
justify-content: left;
margin-left: 40px;
cursor: pointer;
border-radius: 8px;
background-color: white;
transition-duration: 1s;
}
.more:hover{
      transition-duration: 1s;
      background-color: rgb(206, 213, 225);
}
@media (max-width: 1080px) {
  .allpacks {
  grid-template-columns: repeat(1, 1fr); 
  gap: 10px ;
  }
}
@media (max-width: 768px) {
  .inboxpic{
    width: 350px;
    height: 250px;
  }
.allpacks{
  padding: 0px 0px;
}
}

</style>
<script>
export default{
      name: 'FirstBlock'
}
</script>