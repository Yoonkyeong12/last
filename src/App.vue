<template>

  <main class="black-bg" v-if="모달창열렸니 == true">

   <section v-if="학년==1 & 반 ==1">
    <div class="white-bg">
     <div>

        <table border="1">
          <tr>
            <td>{{학년}}-{{반}}</td>
            <td>월요일</td>
            <td>화요일</td>
            <td>수요일</td>
            <td>목요일</td>
            <td>금요일</td>
          </tr>

          <tr>
            <td>1교시</td>
            <td>{{importvalue1[1].Column3}}</td>
            <td>{{importvalue1[2].Column10}}</td>
            <td>{{importvalue1[3].Column17}}</td>
            <td>{{importvalue1[4].Column24}}</td>
            <td>{{importvalue1[5].Column31}}</td>
          </tr>
          
          <tr>
            <td>2교시</td>
            <td>{{importvalue1[1].Column4}}</td>
            <td>{{importvalue1[2].Column11}}</td>
            <td>{{importvalue1[3].Column18}}</td>
            <td>{{importvalue1[4].Column25}}</td>
            <td>{{importvalue1[5].Column32}}</td>
          </tr>

          <tr>
            <td>3교시</td>
            <td>{{importvalue1[1].Column5}}</td>
            <td>{{importvalue1[2].Column12}}</td>
            <td>{{importvalue1[3].Column19}}</td>
            <td>{{importvalue1[4].Column26}}</td>
            <td>{{importvalue1[5].Column33}}</td>
          </tr>

           <tr>
            <td>4교시</td>
            <td>{{importvalue1[1].Column6}}</td>
            <td>{{importvalue1[2].Column13}}</td>
            <td>{{importvalue1[3].Column20}}</td>
            <td>{{importvalue1[4].Column27}}</td>
            <td>{{importvalue1[5].Column34}}</td>
          </tr>

          <tr>
            <td>5교시</td>
            <td>{{importvalue1[1].Column7}}</td>
            <td>{{importvalue1[2].Column14}}</td>
            <td>{{importvalue1[3].Column21}}</td>
            <td>{{importvalue1[4].Column28}}</td>
            <td>{{importvalue1[5].Column35}}</td>
          </tr>

          <tr>
            <td>6교시</td>
            <td>{{importvalue1[1].Column8}}</td>
            <td>{{importvalue1[2].Column15}}</td>
            <td>{{importvalue1[3].Column22}}</td>
            <td>{{importvalue1[4].Column29}}</td>
            <td>{{importvalue1[5].Column36}}</td>
          </tr>

          <tr>
            <td>7교시</td>
            <td>{{importvalue1[1].Column9}}</td>
            <td>{{importvalue1[2].Column16}}</td>
            <td>{{importvalue1[3].Column23}}</td>
            <td>{{importvalue1[4].Column30}}</td>
            <td>{{importvalue1[5].Column37}}</td>
          </tr>
          
       </table>

     </div>
      <button @click="모달창열렸니 = false">닫기</button>
     </div>



   </section>

   <section v-else-if="학년==1 & 반 ==2">
    <div class="white-bg">
     <div>

        <table border="1">
          <tr>
            <td>{{학년}}-{{반}}</td>
            <td>월요일</td>
            <td>화요일</td>
            <td>수요일</td>
            <td>목요일</td>
            <td>금요일</td>
          </tr>

          <tr>
            <td>1교시</td>
            <td>{{importvalue2[1].Column3}}</td>
            <td>{{importvalue2[2].Column10}}</td>
            <td>{{importvalue2[3].Column17}}</td>
            <td>{{importvalue2[4].Column24}}</td>
            <td>{{importvalue2[5].Column31}}</td>
          </tr>
          
          <tr>
            <td>2교시</td>
            <td>{{importvalue2[1].Column4}}</td>
            <td>{{importvalue2[2].Column11}}</td>
            <td>{{importvalue2[3].Column18}}</td>
            <td>{{importvalue2[4].Column25}}</td>
            <td>{{importvalue2[5].Column32}}</td>
          </tr>

          <tr>
            <td>3교시</td>
            <td>{{importvalue2[1].Column5}}</td>
            <td>{{importvalue2[2].Column12}}</td>
            <td>{{importvalue2[3].Column19}}</td>
            <td>{{importvalue2[4].Column26}}</td>
            <td>{{importvalue2[5].Column33}}</td>
          </tr>

           <tr>
            <td>4교시</td>
            <td>{{importvalue2[1].Column6}}</td>
            <td>{{importvalue2[2].Column13}}</td>
            <td>{{importvalue2[3].Column20}}</td>
            <td>{{importvalue2[4].Column27}}</td>
            <td>{{importvalue2[5].Column34}}</td>
          </tr>

          <tr>
            <td>5교시</td>
            <td>{{importvalue2[1].Column7}}</td>
            <td>{{importvalue2[2].Column14}}</td>
            <td>{{importvalue2[3].Column21}}</td>
            <td>{{importvalue2[4].Column28}}</td>
            <td>{{importvalue2[5].Column35}}</td>
          </tr>

          <tr>
            <td>6교시</td>
            <td>{{importvalue2[1].Column8}}</td>
            <td>{{importvalue2[2].Column15}}</td>
            <td>{{importvalue2[3].Column22}}</td>
            <td>{{importvalue2[4].Column29}}</td>
            <td>{{importvalue2[5].Column36}}</td>
          </tr>

          <tr>
            <td>7교시</td>
            <td>{{importvalue2[1].Column9}}</td>
            <td>{{importvalue2[2].Column16}}</td>
            <td>{{importvalue2[3].Column23}}</td>
            <td>{{importvalue2[4].Column30}}</td>
            <td>{{importvalue2[5].Column37}}</td>
          </tr>
          
       </table>

     </div>
      <button @click="모달창열렸니 = false">닫기</button>
    </div>
   </section>

   <section v-else-if="학년==1 & 반 ==3">
    <div class="white-bg">
     <div>

        <table border="1" class='tabel'>
          <tr>
            <td>{{학년}}-{{반}}</td>
            <td>월요일</td>
            <td>화요일</td>
            <td>수요일</td>
            <td>목요일</td>
            <td>금요일</td>
          </tr>

          <tr>
            <td>1교시</td>
            <td>{{importvalue3[1].Column3}}</td>
            <td>{{importvalue3[2].Column10}}</td>
            <td>{{importvalue3[3].Column17}}</td>
            <td>{{importvalue3[4].Column24}}</td>
            <td>{{importvalue3[5].Column31}}</td>
          </tr>
          
          <tr>
            <td>2교시</td>
            <td>{{importvalue3[1].Column4}}</td>
            <td>{{importvalue3[2].Column11}}</td>
            <td>{{importvalue3[3].Column18}}</td>
            <td>{{importvalue3[4].Column25}}</td>
            <td>{{importvalue3[5].Column32}}</td>
          </tr>

          <tr>
            <td>3교시</td>
            <td>{{importvalue3[1].Column5}}</td>
            <td>{{importvalue3[2].Column12}}</td>
            <td>{{importvalue3[3].Column19}}</td>
            <td>{{importvalue3[4].Column26}}</td>
            <td>{{importvalue3[5].Column33}}</td>
          </tr>

           <tr>
            <td>4교시</td>
            <td>{{importvalue3[1].Column6}}</td>
            <td>{{importvalue3[2].Column13}}</td>
            <td>{{importvalue3[3].Column20}}</td>
            <td>{{importvalue3[4].Column27}}</td>
            <td>{{importvalue3[5].Column34}}</td>
          </tr>

          <tr>
            <td>5교시</td>
            <td>{{importvalue3[1].Column7}}</td>
            <td>{{importvalue3[2].Column14}}</td>
            <td>{{importvalue3[3].Column21}}</td>
            <td>{{importvalue3[4].Column28}}</td>
            <td>{{importvalue3[5].Column35}}</td>
          </tr>

          <tr>
            <td>6교시</td>
            <td>{{importvalue3[1].Column8}}</td>
            <td>{{importvalue3[2].Column15}}</td>
            <td>{{importvalue3[3].Column22}}</td>
            <td>{{importvalue3[4].Column29}}</td>
            <td>{{importvalue3[5].Column36}}</td>
          </tr>

          <tr>
            <td>7교시</td>
            <td>{{importvalue3[1].Column9}}</td>
            <td>{{importvalue3[2].Column16}}</td>
            <td>{{importvalue3[3].Column23}}</td>
            <td>{{importvalue3[4].Column30}}</td>
            <td>{{importvalue3[5].Column37}}</td>
          </tr>
          
       </table>

     </div>
      <button @click="모달창열렸니 = false">닫기</button>
    </div>
   </section>


  <div v-else  class="error-white-bg">
  학년 반을 입력하세요.
  <br>
  <button @click="모달창열렸니 = false">닫기</button>
  </div>

</main>

  <div class="menu">
    <a href = localhost:80/index.php>개금고 홈페이지</a>
    <a href =./borrow.vue>개금고 청원사이트</a>
    
  </div>

<h2>이번주(9/20) 수요일 6,7교시는 {{wed_67[0]}} 입니다.</h2>
  <div class='main'>
    <img src="./assets/newjeans.jpg" class = "room-img">
    <br>
    <br>
    <input  v-model="학년" type ="number" min ='1' max = '3' placeholder="학년" class='button'>
    <input  v-model="반" type ="number" min = '1' max = '7' placeholder="반" class='button'>
    <br>
    <br>
    <button @click = "모달창열렸니 = true" class="button1">{{학년}}학년 {{반}}반 시간표 조회하기</button>
    
    <br>
  
  
   
  </div>
   
   <footer>
    <img src = "./assets/kkhslogo.jpg" class="logo">
    <div class="info">
      <span>만든이 : 윤상경</span>
      <span>EMAIL : skyeong1228@naver.com</span>
    </div>

    <p class="copyright">
      &copy; <span class="this-year"></span> Yoon s k. All Rights Reseved.
    </p>
    

 
  </footer>

  <div id="app">
        <router-link to="./main.vue">main</router-link>
        <router-link to="/info">info</router-link>
        <!-- convert -->
        <!-- <a href="#/main" class="">main</a> -->
		<router-view></router-view>	
	</div>

  </template>
  
<script>
import data1_1 from './assets/1-1.js';
import data1_2 from './assets/1-2.js';
import data1_3 from './assets/1-3.js';

 export default {
  name: 'App',
  data(){
    return{
     wed_67 : ['동아리','교육'],
     importvalue1 : data1_1,
     importvalue2 : data1_2,
     importvalue3 : data1_3,
     모달창열렸니: false,
     메뉴들 : [ '개금고등학교 시간표' , '개금고 사이트', '개금고 청원사이트', ],
     학년 : "",
     반 : ""
    }
  }
  

}

</script>

<style>

body {
  margin : 0
}

div {
  box-sizing: border-box;
   min-height: 0%;
 
}



.black-bg {
  width : 100%; height: 100%;
  background: rgba(0,0,0,0.5);
  position : fixed;
  padding: 20px ;
}
.white-bg {
  width : 100%; 
  background: white;
  border-radius: 8px;
  padding: 20px ;

}
.error-white-bg {
  width : 30%; 
  background: white;
  border-radius: 8px;
  padding: 20px ;
  margin: 0 auto;
  

}
.room-img{
  width : 70%;
  margin-top: 40px;
  
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
 
  
}

.button {
  width : 10%;
  height : 20%;

}

.button1{
  width : 20%;

}

.menu {
  background: darkslateblue;
  padding : 15px;
  border-radius: 5px;
}

.menu a {
  color: white;
  padding : 10px
}
.table{
   display: flex;
}


footer {
  background-color: #272727;
  border-top: 1px solid #333;
}
footer .inner {
  padding: 40px 0 60px 0
}
footer .menu {
  display: flex;
  justify-content: center;
}
footer .menu li {
  position: relative;
}
footer .menu li::before {
  content: "";
  width: 3px;
  height: 3px;
  background-color: #555;
  position: absolute;
  top: 0;
  bottom: 0;
  right: -1px;
  margin: auto;
}
footer .menu li:last-child::before {
  display: none;
}
footer .menu li a {
  color: #ccc;
  font-size: 12px;
  font-weight: 700;
  padding: 15px;
  display: block;
}
footer .menu li a.green {
  color: #669900
}
footer .btn-group {
  margin-top: 20px;
  display: flex;
  justify-content: center;
}
footer .btn-group .btn {
  font-size: 12px;
  margin-right: 10px;
}
footer .btn-group .btn:last-child {
  margin-right: 0px;
}
footer .info {
  margin-top: 30px;
  text-align: center;
}
footer .info span {
  margin-right: 20px;
  color: #999;
  font-size: 12px;
}
footer .info span:last-child {
  margin-right: 0;
}
footer .copyright {
  color: #999;
  font-size: 12px;
  text-align: center;
  margin-top: 12px;
}
footer .logo {
  margin: 10px auto 0;
  width : 10%;
}

</style>
