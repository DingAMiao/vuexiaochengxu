<template>
          <div class='page_row' bindtap="suo">
    <view class="search">
      <view class="df search_arr">
        <icon class="searchcion" size='20' type='search'></icon>
        <input class="" disabled placeholder="请输入关键字" value="{{searchValue}}"/>
      </view>
    </view>
    <view class='sousuo'>搜索</view>
          </div>
</template>
<style>
    .search{  
      width: 80%;  
    }  
    .search_arr {  
      border: 1px solid #d0d0d0;  
      border-radius: 10rpx;  
      margin-left: 5rpx;  
    }  
    .search_arr input{  
      margin-left: 60rpx;  
      height: 60rpx;  
      border-radius: 5px;  
    }  
    .bc_text {  
      line-height: 68rpx;  
      height: 68rpx;  
      margin-top: 34rpx;  
    }  
      
    .sousuo {  
      margin-left: 20rpx;  
      width: 15%;  
      line-height: 150%;  
      text-align: center;  
      border: 1px solid #d0d0d0;  
      border-radius: 10rpx;  
    }  
    .page_row{  
      display: flex;  
      flex-direction: row  
    }  
    .searchcion {  
      margin: 10rpx 10rpx 10rpx 10rpx;  
      position: absolute;  
      left:5rpx;  
      z-index: 2;  
      width: 20px;  
      height: 20px;  
      text-align: center;  
    }  
 
</style>
