<template>
  <div clas='main'>
  <h1>Nguyễn Anh Tuấn</h1>
            <p>Software developer and game designer</p>
            <i>
                Give a man a game and he will have fun for a day. Teach a man to make game and he will never have fun again.
            </i>
            <p>Author: someone on the internet</p>
                <div class='grid'>
                    <div class='card'>
                        <h2>Job:</h2>
                        <p>Frontend Developer</p>
                        <p>Game Designer and Developer</p>
                        <p>A.I. Developer (sometimes)</p>
                        <h2>Education:</h2>
                        <p>National Economics University: Information Technology</p>
                    </div>
                    <div class='card'>
                        <h2>Skills</h2>
                        <p>HTML, JS, CSS</p>
                        <p>Framework and Library: ReactJS, NextJS, Vue, JQuery</p>
                        <p>C# and Unity</p>
                        <p>C++ and Unreal</p>
                    </div>
                    <div class='card'>
                        <h2>My specs</h2>
                        <h4>ASUS ZenBook laptop</h4>
                        <p>Intel Core i5</p>
                        <p>8GB RAM</p>
                        <p>512GB SSD</p>
                        <h4>IDEs and Text Editors</h4>
                        <p>Visual Studio Code</p>
                        <p>Visual Studio Community 2022</p>
                    </div>
                  </div>
                  <h1>Các dự án đã thực hiện</h1>
                <h1>2020</h1>
                <div class='grid'>
                    <div class='project'>
                                <h2>COIVD-19 Tracker</h2>
                                <p>Trang web thống kê số ca COVID-19 tại Việt Nam</p>
                                <h4>Công nghệ: React</h4>
                    </div>
                </div>
                <h1>2021</h1>
                <div class='grid'>
                    <div class='project'>
                                <h2>FireNancy</h2>
                                <p>Trang web tài chính</p>
                                <h4>Công nghệ: React</h4>
                    </div>
                    <div class='project'>
                                <h2>2D Game</h2>
                                <p>Tựa game 2D nho nhỏ</p>
                                <h4>Engine: Unity</h4>
                    </div>
                </div>
                <h1>2022</h1>
                <div class='grid'>
                    <div class='project'>
                                <h2>THPTQG Helper</h2>
                                <p>Trang web tính điểm thi THPT</p>
                                <h4>Công nghệ: React</h4>
                    </div>
                    <div class='project'>
                                <h2>2D Game</h2>
                                <p>Lại là một tựa game 2D nho nhỏ</p>
                                <h4>Engine: Unity</h4>
                    </div>
                </div>
  </div>
</template>

<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.main {
  min-height: 100vh;
  padding: 4rem 0;
  flex: 1;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
.grid {
  display: flex;
  align-items: flex-start;
  justify-content: center;
  flex-wrap: wrap;
}

.project, .card {
  text-align: left;
  color: inherit;
  text-decoration: none;
  border: 1px solid #eaeaea;
  border-radius: 15px;
  transition: color 0.15s ease, border-color 0.15s ease;
}

.project {
  margin: 1rem;
  padding: 1.5rem;
  max-width: 300px;
}

.card {
  margin: 0.5rem;
  padding: 1rem;
  max-width: 250px;
}

.project:hover,
.project:focus,
.project:active,
.card:hover,
.card:focus,
.card:active {
  color: #0070f3;
  border-color: #0070f3;
}

.project h2 {
  margin: 0 0 1rem 0;
}

.project p {
  margin: 0;
  font-size: 1.25rem;
}


</style>