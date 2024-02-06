<script>
export default {
    name: "LinkComponent"
}
</script>

<template>
    <div id="links">
        <h1>Links</h1>
        <div class="container">
            
            <div class="column1">
                
                <h2>Resources</h2>
                <div class="resource-items">
                    <div class="content">
                        <div class="icon"><img alt="github" src="@/assets/images/AboutPage/github.png"/></div>
                        <div class="content-text"><p><a href="www.github.com/blitz">Github</a></p></div>                            
                    </div>
                    <div class="content">
                        <div class="icon"><img alt="tutorials" src="@/assets/images/AboutPage/github.png"/></div>
                        <div class="content-text"><p><a href="">Tutorials</a></p></div>
                    </div>
                    <div class="content">
                        <div class="icon"><img alt="faq" src="@/assets/images/AboutPage/faq.png"/></div>
                        <div class="content-text"><p><a href="www.blitz.com/faq">FAQ</a></p></div>
                    </div>
                </div>
            
            </div>
            
            <div class="column2">
                    
                <h2>Contact</h2>
                <div class="contact-info">
                    <div class="content">
                        <div class="icon"><img alt="email" src="@/assets/images/AboutPage/email.png"/></div>
                        <div class="content-text"><p>Email: <a href="">bothsblitz@gmail.com</a></p></div>
                    </div>
                </div>
            
            </div>

            <div class="column3">
                    
                <h2>Socials</h2>
                <div class="social-handles">
                    <div class="content">
                        <div class="icon"><img alt="x" src="@/assets/images/AboutPage/x.png"/></div>
                        <div class="content-text"><p><a href="">X</a></p></div>    
                    </div>
                    <div class="content">
                        <div class="icon"><img alt="discord" src="@/assets/images/AboutPage/discord.png"/></div>
                        <div class="content-text"><p><a href="">Discord</a></p></div>
                    </div>
                    <div class="content">
                        <div class="icon"><img alt="blog" src="@/assets/images/AboutPage/blog.png"/></div>
                        <div class="content-text"><p><a href="www.devlog.com/blitz">Devlog</a></p></div>
                    </div>
                </div>               

            </div>

        </div>
    </div>
</template>

<style scoped>
#link {
    margin: 0;
    padding: 20px 0px 20px 0px;
    width: 100vw;

}

h1 {
  text-align: center;
  font-family: "Garnett";
  font-size: 50px;
  font-style: normal;
  font-weight: 800;
  line-height: normal;
  margin-top: 20px;
  padding-bottom: 0px;
  color: #FFF;
}

.column1 h2, .column2 h2, .column3 h2 {
  text-align: center;
  font-family: "Garnett";
  font-size: 30px;
  font-style: normal;
  font-weight: 800;
  line-height: normal;
  margin-top: 20px;
  padding-bottom: 0px;
  color: #FFF;
}

p {
  text-align: center;
  font-family: "DM Mono";
  font-size: 20px;
  font-style: normal;
  font-weight: 400;
  line-height: normal;
  margin-top: 10px;
  color: #FFF;
}

.container {
    display: flex;
    padding: 20px;
    width: 90%;
    margin: 0 auto;
}

.column1 {
    flex: 1;
    padding: 20px;
    box-sizing: border-box;
    height: 100%;
}

.column2 {
    flex: 1;
    padding: 20px;
    box-sizing: border-box;
    width: 100%;
    height: 100%;
    margin-left: 10px;
}

.column3 {
    flex: 1;
    padding: 20px;
    box-sizing: border-box;
    height: 100%;
    margin-left: 10px;
}

.content {
    display: flex;
    height: 100%;
    margin: 0 auto;
    width: 90%;
}

.content-text p {
    padding: 0;
}

.content-text a {
    padding: 0;
    color: #FFF;
    text-decoration: none;
}

.icon {
    height: 10%;
    padding: 0;
    margin: 0;
    width: 10%;
}
.icon img {
    width: 100%;
    height: 100%;
    padding: 0;
}

.content-text {
    margin-left: 10%;
}

.resource-items, .social-handles  {
    width: 90%;
}

.contact-info {
    border-left: solid #FFF 0.5px;
    border-right: solid #FFF 0.5px;
    padding-left: 20px;
    padding-right: 20px;
    height: 100%;
}

</style>