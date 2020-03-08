<template>

	<view class="centent">
		<view class="h3">选择疫情项目</view>
		<ul>
			<li class="come">
				<a href="http://cr.yq.jieao.xin/h5">
					<!-- <img src="" /> -->
					<span class="title">出入人员登记系统</span>
					<span class="text">疫情期间严格执行出入登记。支持出入人员自助扫码填表，支持管理员查看、统计、搜索。</span>
				</a>
			</li>
			<li class="health">
				<a href="http://xs.yq.jieao.xin/h5">
					<!-- <img src="" /> -->
					<span class="title">学生健康报备管理系统</span>
					<span class="text">学生健康情况排查。分为学生、家长、老师，不同角色有不用的界面和管理功能。有更强大的统计功能。</span>
				</a>
			</li>
			<li class="goods">
				<a href="http://wz.yq.jieao.xin/h5">
					<!-- <img src="" /> -->
					<span class="title">物资管理系统</span>
					<span class="text">单位用于记录从物资的领取和派发记录，从上级单位领取了什么物资，型号、数量、领取时间。 </span>
				</a>
			</li>
		</ul>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				
			}
		},
		methods: {

		}
	}
</script>

<style>

	*{
		margin:0;
		padding:0;
	} 
	
	ul li{
	   list-style-type:none;
	   padding: 1rem;
	   margin-top: 1rem;
	   color: #ffffff;
	   border-radius: 1rem;
	}
	.h3{
		margin: 1rem 0 ;
		font-size: 1rem;
	}
	span{
		display:inline-block
	}
	.centent{
	   width: 90%;
	   margin: 0 auto;
	   font-size: 14px;
	}
	
	.centent .come{
		border:1px solid #00AA00;
		background: #00AA00;
		
	}
	.centent .health{
		border:1px solid #009FCC;
		background:#009FCC;
		
	}
	.centent .goods{
		border:1px solid #d43f3a ;
		background: #d43f3a ;
		
	}
	.centent .title{
		font-size: 1rem;
		margin-bottom: 0.5rem;
		font-weight: bold;
	}
	.centent .text{
		font-size: 0.8rem;
	}
	a {
	    text-decoration: none;
		color: white;
	}
	
	a:link {
	    text-decoration: none;
	}
	
	a:visited {
	    text-decoration: none;
	}
	
	a:hover {
	    text-decoration: none;
		-webkit-tap-highlight-color: transparent;
	}
			
	a:active {
	    text-decoration: none;
	}
</style>
