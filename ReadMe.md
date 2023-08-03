<div class="intro">
  <div class="dot"></div> 
  <div class="dot"></div>
  <div class="dot"></div> 
</div>

<style>
.intro {
  text-align: center;
}  
.dot {
  height: 25px;
  width: 25px;
  background-color: #333;
  border-radius: 50%;  
  display: inline-block;
  animation: pulse 1s infinite;
}
@keyframes pulse {
  0% {
    transform: scale(1); 
  }
  50% {
    transform: scale(1.2);
  }    
  100% {
    transform: scale(1);
  }
}
</style>


