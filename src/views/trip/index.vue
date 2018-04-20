<template>
	<div>
		<div class="app-head">
          <div class="app-head-inner">
                    
              <div class="head-nav">
                   <ul class="nav-list">
                      <li>用户名</li>
                      <li>登录</li>
                      <li class="nav-pile">|</li>
                      <li>注册</li>
                      <li>退出</li>
                      <li class="nav-pile">|</li>
                      <li>关于</li>
                   </ul>
              </div>
          </div>
        </div>
		<footer-nav v-bind:class="{'isIndex':isNowPage}"></footer-nav>
	</div>
</template>

<script>
	import FooterNav from '../../components/footer.vue'
	export default{
		components: {
			FooterNav
		},
		data(){
			return{
				isNowPage: true
			}
		}
	}
</script>
