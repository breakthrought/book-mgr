<template>
    <div class="auth">
        <div class="bg"></div>
        <div class="title-info">
            
            <img src="https://ncstatic.clewm.net/rsrc/2020/1016/02/4757e4910cb527fc040d019a93ded74f.png?x-oss-process=image/resize,w_750/format,gif/sharpen,100/quality,Q_80/interlace,1/auto-orient,1" alt="erro">
            <h2 class="title">图书管理系统后台</h2>
        </div>
        <div class="form">
            <a-tabs >
              <a-tab-pane key="1" tab="登录">
                <div class="item">
                    <a-input size="large" placeholder="账号" >
                        <template #prefix>
                            <User-Outlined  />
                        </template>
                    </a-input>
                </div>
                <div class="item">
                    <a-input size="large" placeholder="密码" >
                        <template #prefix>
                           <Lock-Outlined />
                        </template>
                    </a-input>
                </div>
                <div class="item">
                    <a ref="">忘记密码</a>

                </div>
                <div class="item">
                    <a-button size="large" type="primary">登入</a-button>

                </div>
              </a-tab-pane>
              <a-tab-pane key="2" tab="注册">
                <div class="item">
                    <a-input size="large" placeholder="账号" >
                        <template #prefix>
                            <User-Outlined  />
                        </template>
                    </a-input>
                </div>
                <div class="item">
                    <a-input size="large" placeholder="密码" >
                        <template #prefix>
                           <Lock-Outlined />
                        </template>
                    </a-input>
                </div>
                <div class="item">
                    <a-input size="large" placeholder="邀请码" >
                        <template #prefix>
                           <Mail-Outlined />
                        </template>
                    </a-input>
                </div>

                <div class="item">
                    <a-button size="large" type="primary">注册</a-button>

                </div>

              </a-tab-pane>
    
            </a-tabs>

        </div>

    </div>
</template>

<script  src="./index.js" >
   
</script>

<style lang="scss" scoped >
 @import url('./index.scss');
</style>