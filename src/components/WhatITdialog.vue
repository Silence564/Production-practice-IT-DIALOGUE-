<template>
    <div class="frame66">
      <div class="text2">Что такое ИТ Диалог</div>
      <div class="frame65">
        <div class="ItemAbout">
          <div class="text3">Мероприятия</div>
          <div class="block1">
            <div class="block-button"><button class="button1">Узнать больше</button></div>
            <img class="Ellipse4" src="../../public/image/Ellipse4.png" />
          </div>  
        </div>
        <div class="ItemAbout">
          <div class="text3">Экспертный клуб</div>
          <div class="block1">
            <router-link to="/page_club"><div class="block-button"><button class="button1">Узнать больше</button></div></router-link>
            <img class="Ellipse4" src="../../public/image/Ellipse2.png" />
          </div>  
        </div>
        <div class="ItemAbout">
          <div class="text3">Медиапроект</div>
          <div class="block1">
            <div class="block-button"><button class="button1">Узнать больше</button></div>
            <img class="Ellipse4" src="../../public/image/Ellipse3.png" />
          </div>  
        </div>
      </div>
    </div>
 </template>
<script>
export default {
name: 'What-it-dialog'
}
</script>
<style lang="scss" scoped>
.frame66{
  max-width: 1440px; 
  width: 100%;
  height: 100%; 
  padding-left: 108px; 
  padding-right: 108px; 
  padding-top: 56px; 
  padding-bottom: 56px; 
  flex-direction: column; 
  justify-content: flex-start; 
  align-items: flex-start; 
  gap: 40px; 
  display: inline-flex;
}

.text2{
  align-self: stretch; 
  color: #1D2329; 
  font-size: 40px; 
  font-weight: 700; 
  line-height: 43.20px; 
  word-wrap: break-word;
}

.text3{
  color: #1D2329; 
  font-size: 2.2vw; 
  font-weight: 600; 
  line-height: 30.24px; 
  word-wrap: break-word;
}

.frame65{
  max-width: 1224px; 
  width: 100%;
  height: 100%; 
  justify-content: flex-start; 
  align-items: flex-start; 
  gap: 20px; 
  display: inline-flex;
  flex-wrap: wrap;
}

.ItemAbout{
  width: 32%;
  height: 100%; 
  padding: 20px; 
  background: #F5F8FC; 
  border-radius: 20px; 
  flex-direction: column; 
  justify-content: space-between; 
  align-items: flex-start; 
  display: inline-flex;
  overflow: hidden;
}

.button1{
  width: 162px; 
  height: 40px;
  padding-left: 20px; 
  padding-right: 20px; 
  border-radius: 12px; 
  text-align: center;
  font-size: 16px; 
  font-weight: 600; 
  line-height: 16px; 
  letter-spacing: 0.32px; 
  word-wrap: break-word;
  background: white;
  border: 1px #2B71C2 solid; 
  color: #1D2329;
  white-space: nowrap;
  cursor:pointer;

  &:hover{
  border: none;  
  background: #2B71C2; 
  color: white; 
}
}

.block1{
  display: inline-flex;
  flex-direction: row;
  
}

.block-button{
  padding-top: 10vw;
  padding-right: 0.9vw;
}

.Ellipse4{ padding-top: 3vw; height: auto; width: 50%;}
</style>