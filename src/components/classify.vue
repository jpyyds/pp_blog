<template>
    <div class="card-contents">
        <div class="card-title">
            <svg t="1624863169073" class="icon" viewBox="0 0 1024 1024" version="1.1" xmlns="http://www.w3.org/2000/svg" p-id="2419" width="26" height="26"><path d="M772.8 880H491.2c-86.4 0-155.2-70.4-155.2-155.2v-46.4c0-86.4 70.4-155.2 155.2-155.2h281.6c86.4 0 155.2 70.4 155.2 155.2v46.4c0 84.8-70.4 155.2-155.2 155.2z" fill="#96E8BA" p-id="2420"></path><path d="M480 628.8c-4.8 0-8-1.6-12.8-3.2L116.8 387.2c-6.4-4.8-9.6-11.2-9.6-19.2s3.2-14.4 9.6-19.2l134.4-91.2c9.6-6.4 24-4.8 30.4 6.4 6.4 9.6 4.8 24-6.4 30.4L169.6 368 480 579.2l128-88 33.6-121.6c1.6-6.4 8-12.8 14.4-14.4 6.4-3.2 14.4-1.6 20.8 3.2l64 44.8 51.2-35.2L480 156.8l-56 38.4c-9.6 6.4-24 4.8-30.4-6.4-6.4-9.6-4.8-24 6.4-30.4L468.8 112c8-4.8 17.6-4.8 25.6 0l350.4 238.4c6.4 4.8 9.6 11.2 9.6 19.2s-3.2 14.4-9.6 19.2L752 448c-8 4.8-17.6 4.8-25.6 0l-49.6-35.2-27.2 99.2c-1.6 4.8-4.8 9.6-9.6 12.8l-147.2 100.8c-3.2 1.6-8 3.2-12.8 3.2z" fill="#103E26" p-id="2421"></path><path d="M313.6 264c-6.4 0-14.4-3.2-19.2-9.6-6.4-9.6-4.8-24 6.4-30.4l44.8-30.4c9.6-6.4 24-4.8 30.4 6.4s4.8 24-6.4 30.4l-44.8 30.4c-1.6 3.2-6.4 3.2-11.2 3.2zM480 740.8c-4.8 0-8-1.6-12.8-3.2L116.8 499.2c-9.6-6.4-12.8-20.8-6.4-30.4 6.4-9.6 20.8-12.8 30.4-6.4L480 691.2l337.6-230.4c9.6-6.4 24-4.8 30.4 6.4 6.4 9.6 4.8 24-6.4 30.4l-348.8 240c-3.2 1.6-8 3.2-12.8 3.2z" fill="#103E26" p-id="2422"></path><path d="M480 852.8c-4.8 0-8-1.6-12.8-3.2L116.8 611.2c-9.6-6.4-12.8-20.8-6.4-30.4 6.4-9.6 20.8-12.8 30.4-6.4L480 803.2l337.6-230.4c9.6-6.4 24-4.8 30.4 6.4 6.4 9.6 4.8 24-6.4 30.4l-348.8 240c-3.2 1.6-8 3.2-12.8 3.2z" fill="#103E26" p-id="2423"></path></svg>
            <span style="margin-left:5px">分类</span>
        </div>
        <div class="classify-item"><span class="classify-font">学习记录</span> <span class="classify-count">5</span></div>
        <div class="classify-item"><span class="classify-font">推荐</span> <span class="classify-count">2</span></div>
    </div>
</template>
<style>


.classify-item{
    display: flex;
    flex-direction: row;
    flex-wrap: nowrap;
    width: 95%;
    justify-content: space-between;
    margin: 5px auto;
}
.classify-count{
    margin-right: 30px;
}
.classify-font{
    margin-left: 30px;
}
.classify-item:hover{
     background: #313131;
      color: aliceblue;
      border-radius: 10px;
}
</style>