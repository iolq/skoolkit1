<template>
  <div class>
    <div class="text-center">
      <v-alert color="#DB2C27" dark>
        เข้าร่วมกิจกรรม Workshop
        เพื่อร่วมเป็นส่วนหนึ่งในการพัฒนานวัตกรรมการศึกษา
        <u class="pointer" @click="$router.push('/workshop')">คลิกที่นี่</u>
      </v-alert>
    </div>

    <v-row>
      <div class="d-flex">
        <v-row align="center" class="justify-start">
          <v-img src="SKOOLKIT โลโก้สีดำ.png" width="350" height="120"> </v-img>
          <div class="d-flex">
            <v-col class="tabs">
              <div class="d-flex">
                <v-col>
                  <p class="pointer" @click="$router.push('/')">คุณสมบัติ</p>
                </v-col>
                <v-col cols="3">
                  <p class="pointer" @click="$router.push('/article')">
                    บทความ
                  </p>
                </v-col>
                <v-col cols="3">
                  <p class="pointer" @click="$router.push('/trial')">
                    ทดลองการใช้งาน
                  </p>
                </v-col>
                <v-col cols="7" />
                <v-col class="tabs" cols="3">
                  <p class="pointer">เข้าร่วมควิช</p>
                </v-col>
                <v-col>
                  <v-btn color="#DB2C27" rounded large dark>เข้าสู่ระบบ</v-btn>
                </v-col>
              </div>
            </v-col>
          </div>
        </v-row>
      </div>
    </v-row>
    <v-container>
      <v-container>
        <div>
          <v-container>
            <v-container>
              <h1 class="text-left">
                <strong
                  >SKOOLKIT  แพลตฟอร์มจัดการเรียนการสอนเเบบ Active Learning
                </strong>
              </h1>
              <h1 class="text-left">
                <strong
                  >ที่รวบรวมทั้งสื่อเเละเครื่องมือไว้ในที่เดียวให้ได้ใช้งานฟรี</strong
                >
              </h1>
            </v-container>
            <v-container
              ><h2 class="text-left font-weight-thin">
                เพียงลงทะเบียนฟอร์มด้านล่าง และรอการติดต่อกลับจากทีมงาน
              </h2></v-container
            >
          </v-container>
        </div>

        <iframe
          src="https://docs.google.com/forms/d/e/1FAIpQLScaPHs4tbPSD0w_tFeiusKvYUxauci8tP8zTSfiWk7z-BWnow/viewform?embedded=true"
          width="640"
          height="864"
          frameborder="0"
          marginheight="0"
          marginwidth="0"
          >กำลังโหลด…</iframe
        >
      </v-container>
    </v-container>

    <v-footer color="black" dark>
      <v-container>
        <v-row class="text-left">
          <v-col cols="3.5">
            <p class="pointer" @click="$router.push('/')">คุณสมบัติ</p>
            <p class="pointer" @click="$router.push('/article')">บทความ</p>
            <p class="pointer" @click="$router.push('/trial')">
              ทดลองการใช้งาน
            </p>
            <p class="pointer" @click="$router.push('/workshop')">
              เข้าร่วมกิจกรรม workshop
            </p>
          </v-col>
          <v-col cols="4">
            <div>
              <strong>ติดต่อเรา</strong>
            </div>
            <div class="d-flex">
              <v-col>
                <a href="https://www.facebook.com/Skoolkit.thailand">
                  <img
                    src="https://img.icons8.com/material-sharp/48/ffffff/facebook.png" /></a
              ></v-col>
              <v-container><p>SKOOLKIT</p></v-container>
            </div>
            <div class="d-flex">
              <v-col>
                <img
                  src="https://img.icons8.com/material-rounded/48/ffffff/mail.png"
              /></v-col>
              <v-container><div>Contact@skoolkit.co</div></v-container>
            </div>
            <div class="d-flex">
              <v-col>
                <img
                  src="https://img.icons8.com/ios-glyphs/48/ffffff/phone--v1.png"
              /></v-col>

              <v-container
                ><div>063-2329154</div>
                <div>092-9529726</div></v-container
              >
            </div>
          </v-col>
          <v-col cols="3">
            <div><strong>เกี่ยวกับเรา</strong></div>
            <div>
              <v-img src="SKOOLKIT สีขาว.2.png" width="70%"></v-img>
            </div>
            <p>บริษัท เดอะแฟลชโซลูชั่น จำกัด</p>
            <p>สำนักงานเลขที่ 401/62 หมู่ 3</p>
            <p>ตำบลคูคต อำเภอลำลูกกา จังหวัดปทุมธานี</p>
            <p>รหัสไปรณีย์ 12130</p>
          </v-col>
        </v-row>
      </v-container>

      <v-container>
        <h6 class="font-weight-thin">
          Copyright ©2021 SKOOLKIT All Right Reserved
        </h6>
      </v-container>
    </v-footer>
  </div>
</template>

        
            
        