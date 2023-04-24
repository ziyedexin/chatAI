<template>
  <div class="setting">
    <el-container>
      <el-header>
        <transition name="el-zoom-in-top">
          <div v-show="show" class="transition-box">
            <h3>算法社团 AI</h3>
          </div>
        </transition>
      </el-header>
      <el-main>
        <transition name="el-zoom-in-top">
          <div v-show="show" class="transition-box">
            <span>
              <br>感谢萌萌小姐对我的精神支持、申澳对本站的经济赞助。<br>
              本站现已接入OpenAI的Models API、Completions API、Chat API、Audio API、Images API、Files API、Fine-tunes API后续会添加更多有意思的功能进去
            </span>
            <div>
              <a href="https://www.zxhy.club">个人博客</a>---<a href="https://blog.csdn.net/weixin_61084441?spm=1010.2135.3001.5421">CSDN</a>
            </div>
            <div>
              <h3>前路未远，步履不停</h3>
              <h3>愿你我，都能做时间的朋友</h3>
            </div>
          </div>
        </transition>
      </el-main>
    </el-container>
  </div>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      show: false,
    };
  },
  mounted() {
    this.show = true;
  },
};
</script>

<style>
  .transition-box {
    text-align: center;
    margin-top: 5%;
    color: #F2F6FC;
    font-size: 30px;
  }
  h1 {
    color: aliceblue;
    font-size: 80px;
  }
  a {
    text-decoration: none;
    color: #67C23A;
  }
</style>
