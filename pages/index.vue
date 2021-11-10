
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
                  <v-btn color="#DB2C27" dark>เข้าสู่ระบบ</v-btn>
                </v-col>
                <v-col cols="1">
                  <!-- <v-btn outlined>En</v-btn> -->
                </v-col>
              </div>
            </v-col>
          </div>
        </v-row>
      </div>
    </v-row>
    <v-container>
      <v-container>
        <div class="text-left">
          <v-container>
            <h1 class="font-weight-black">
              SKOOLKIT แพลตฟอร์มที่รวบรวมเครื่องมือและสื่อสำหรับจัดการเรียน
            </h1>
            <h1>การสอนแบบ Active Learning อัดแน่นไปด้วย</h1></v-container
          >
          <v-container>
            <div class="d-flex">
              <v-col class="justify-center ps-16" cols="1"
                ><v-container><h1>●</h1> </v-container>
              </v-col>
              <v-col cols="8">
                <v-container>
                  <h4>
                    เครื่องมือเตรียมความพร้อม ไม่ว่าจะเป็นการเช็คชื่อ
                    การแบ่งกลุ่มนักเรียน การโหวต และอื่น ๆ
                  </h4>
                  <h4>
                    ที่เต็มไปด้วยประสบการณ์ใหม่ๆ ให้มีความสนุกและน่าตื่นเต้น
                  </h4>
                </v-container>
              </v-col>
            </div>
          </v-container>
          <v-container>
            <div class="d-flex">
              <v-col class="justify-center ps-16" cols="1"
                ><v-container><h1>●</h1> </v-container>
              </v-col>
              <v-col cols="8">
                <v-container>
                  <h4>
                    สื่อการเรียนการสอนในรูปแบบของเกม ที่เน้นความรู้
                    และการปฏิสัมพันธ์ในชั้นเรียน
                  </h4>
                  <h4>
                    มีหลากหลายบทเรียนทั้งความรู้ในชั้นเรียน และข้อสอบจากสนามต่าง
                    ๆ เช่น O-net
                  </h4>
                </v-container>
              </v-col>
            </div>
          </v-container>
        </div>
        <v-row clas="text-center">
          <div class="d-flex">
            <v-col cols="3">
              <div>
                <v-img src="Group 2774.png" width="50%"></v-img>
                <p class="text-center">เช็คชื่อ</p>
              </div>
            </v-col>
            <v-col cols="2"
              ><div>
                <v-img src="Group random.png" width="80%"></v-img>สุ่ม
              </div></v-col
            >
            <v-col cols="2"
              ><div>
                <v-img src="Group group.png" width="100%"></v-img>แบ่งกลุ่ม
              </div></v-col
            >
            <v-col cols="2"
              ><div>
                <v-img src="Group vote.png" width="100%"></v-img>โหวต
              </div></v-col
            >
            <v-col cols="3">
              <div>
                <v-img src="Group feedback.png" width="65%"></v-img>ฟีดแบค
              </div></v-col
            >
            <v-col cols="3">
              <div>
                <v-img src="Group game.png" width="60%"></v-img>ควิซเกม
              </div></v-col
            >
            <v-col>
              <div>
                <v-img src="Group report.png" width="100%"></v-img>รายงาน
              </div></v-col
            >
          </div>
        </v-row>
        <v-container>
          <v-row>
            <v-col cols="7 pr-1">
              <v-img src="laptop.png"></v-img>
            </v-col>

            <v-col cols="5 ps-1 mt-16">
              <v-container>
                <div class="d-flex">
                  <v-img
                    src="Group 2774.png"
                    max-height="50"
                    max-width="50"
                  ></v-img>
                  <v-col cols="3"
                    ><h2 class="font-weight-thin">เช็คชื่อ</h2></v-col
                  >
                </div>
              </v-container>
              <v-container>
                <div class="text-left">
                  <h3 class="font-weight-thin">
                    ระบบมีการเช็คชื่อที่ง่ายและรวดเร็วที่สุดตั้งแต่
                  </h3>
                  <h3 class="font-weight-thin">
                    ที่เคยมีมา และสามารถดาวน์โหลดและเรียกดูได้
                  </h3>
                  <h3 class="font-weight-thin">ตลอดทั้งปีการศึกษา</h3>
                </div></v-container
              >
            </v-col>
          </v-row>
        </v-container>
        <v-row no-gutters>
          <v-col cols="5 ps-1 mt-16">
            <v-container>
              <div class="d-flex">
                <v-img
                  src="Group random.png"
                  max-height="70"
                  max-width="45"
                ></v-img>
                <v-col cols="3"><h2 class="font-weight-thin">สุ่ม</h2></v-col>
              </div>
            </v-container>
            <v-container>
              <div class="text-left">
                <h3 class="font-weight-thin">
                  สามารถสุ่มนักเรียนขึ้นมาทำกิจกรรม
                </h3>
                <h3 class="font-weight-thin">
                  ระบบมีการเก็บข้อมูลตลอดทุกกิจกรรม
                </h3>
                <h3 class="font-weight-thin">ที่เกิดขึ้นในห้องเรียน</h3>
              </div></v-container
            >
          </v-col>

          <v-col cols="7">
            <v-img src="สุ่ม.png"></v-img>
          </v-col>
        </v-row>
        <v-row no-gutters>
          <v-col cols="7">
            <v-img src="แบ่งกลุ่ม 3.png"></v-img>
          </v-col>
          <v-col cols="5 ps-1 mt-16">
            <v-container>
              <div class="d-flex">
                <v-img
                  src="Group group.png"
                  max-height="50"
                  max-width="60"
                ></v-img>
                <v-col cols="4"
                  ><h2 class="font-weight-thin">แบ่งกลุ่ม</h2></v-col
                >
              </div>
            </v-container>
            <v-container>
              <div class="text-left">
                <h3 class="font-weight-thin">ระบบสามารถแบ่งกลุ่มนักเรียนได้</h3>
                <h3 class="font-weight-thin">
                  อย่างยุติธรรม หมดปัญหาเรื่องเด็กไม่มีกลุ่ม
                </h3>
                <h3 class="font-weight-thin">หรือเข้ากับเพื่อนไม่ได้</h3>
              </div></v-container
            >
          </v-col>
        </v-row>
        <v-row no-gutters>
          <v-col cols="5 ps-1 mt-16">
            <v-container>
              <div class="d-flex">
                <v-img
                  src="Group vote.png"
                  max-height="50"
                  max-width="50"
                ></v-img>
                <v-col cols="3"><h2 class="font-weight-thin">โหวต</h2></v-col>
              </div>
            </v-container>
            <v-container>
              <div class="text-left">
                <h3 class="font-weight-thin">
                  คุณครูสามารถสร้างคำถามเพื่อสอบถาม
                </h3>
                <h3 class="font-weight-thin">
                  ความเห็นของนักเรียนแบบ Real Time
                </h3>
                <h3 class="font-weight-thin">
                  และเก็บข้อมูลทั้งหมดไว้ได้ตลอดปีการศึกษา
                </h3>
              </div></v-container
            >
          </v-col>
          <v-col cols="7">
            <v-img src="โหวต.png"></v-img>
          </v-col>
        </v-row>
        <v-row no-gutters>
          <v-col cols="7">
            <v-img src="ฟีดแบค.png"></v-img>
          </v-col>
          <v-col cols="5 ps-1 mt-16">
            <v-container>
              <div class="d-flex">
                <v-img
                  src="Group feedback.png"
                  max-height="50"
                  max-width="50"
                ></v-img>
                <v-col cols="3"
                  ><h2 class="font-weight-thin">ฟีดแบ็ค</h2></v-col
                >
              </div>
            </v-container>
            <v-container>
              <div class="text-left">
                <h3 class="font-weight-thin">
                  นักเรียนสามารถให้ฟีดแบ็คในทุกคาบเรียน
                </h3>
                <h3 class="font-weight-thin">
                  เพื่อนำข้อมูลมาพัฒนาการจัดการเรียน
                </h3>
                <h3 class="font-weight-thin">
                  การสอนให้มีคุณภาพและตอบโจทย์ผู้เรียน
                </h3>
                <h3 class="font-weight-thin">มากยิ่งขึ้น</h3>
              </div></v-container
            >
          </v-col>
        </v-row>
        <v-row no-gutters>
          <v-col cols="5 ps-1 mt-16">
            <v-container>
              <div class="d-flex">
                <v-img
                  src="Group report.png"
                  max-height="70"
                  max-width="50"
                ></v-img>
                <v-col cols="3"><h2 class="font-weight-thin">รายงาน</h2></v-col>
              </div>
            </v-container>
            <v-container>
              <div class="text-left">
                <h3 class="font-weight-thin">
                  ระบบเก็บข้อมูลจากทุกกิจกรรมที่เกิดขึ้น
                </h3>
                <h3 class="font-weight-thin">
                  ในห้องเรียนทุกคาบเรียน เพื่อให้ทั้งคุณครู
                </h3>
                <h3 class="font-weight-thin">
                  นักเรียน และผู้อำนวยการโรงเรียนเข้าถึง
                </h3>
                <h3 class="font-weight-thin">
                  ข้อมูลเหล่านี้ เพื่อนำข้อมูลไปใช้ประโยชน์
                </h3>
                <h3 class="font-weight-thin">
                  เพื่อพัฒนาคุณภาพการเรียนการสอนต่อไป
                </h3>
              </div></v-container
            >
          </v-col>
          <v-col cols="7">
            <v-img src="report.png"></v-img>
          </v-col>
        </v-row>
        <v-row no-gutters>
          <v-col cols="7">
            <v-img src="เกม 1.png"></v-img>
          </v-col>
          <v-col cols="5 ps-1 mt-16">
            <v-container>
              <div class="d-flex">
                <v-img
                  src="Group game.png"
                  max-height="50"
                  max-width="50"
                ></v-img>
                <v-col cols="3"
                  ><h2 class="font-weight-thin">ควิซเกม</h2></v-col
                >
              </div>
            </v-container>
            <v-container>
              <div class="text-left">
                <h3 class="font-weight-thin">
                  ยกระดับการวัดความเข้าใจผ่านการใช้ควิซ
                </h3>
                <h3 class="font-weight-thin">
                  ที่สามารถวัดผลแบบ Real time ได้
                </h3>
                <h3 class="font-weight-thin">
                  อย่างแม่นยำและถูกต้อง นอกจากได้ความรู้แล้ว
                </h3>
                <h3 class="font-weight-thin">ยังได้ความสนุกสนานไปพร้อมกัน</h3>
              </div></v-container
            >
          </v-col>
        </v-row>
        <div class="text-center">
          <h1 class="font-weight-medium">และบทเรียนอีกมากมาย</h1>

          <h3 class="font-weight-thin">
            รวมเนื้อหาในชั้นเรียน และข้อสอบจากสนามต่าง ๆ
          </h3>
          <h3 class="font-weight-thin">
            สามารถกลับไปทบทวนย้อนหลังได้ทุกที่ ทุกเวลา
          </h3>
        </div>
      </v-container>
      <!-- เอารูปหมุนๆ -->

      <div class="d-flex">
        <v-img src="chem.png" width="14%"></v-img>
        <v-img src="citizen.png" width="14%"></v-img>
        <v-img src="history.png" width="14%"></v-img>
        <v-img src="social.png" width="14%"></v-img>
        <v-img src="astro.png" width="14%"></v-img>
        <v-img src="sci.png" width="14%"></v-img>
        <v-img src="phy.png" width="14%"></v-img>
      </div>

      <div class="d-flex">
        <v-img src="5.png" width="20%"></v-img>
        <v-img src="6.png" width="20%"></v-img>
        <v-img src="7.png" width="20%"></v-img>
        <v-img src="8.png" width="20%"></v-img>
        <v-img src="9.png" width="20%"></v-img>
      </div>

      <v-container>
        <v-col>
          <div class="text-left px-16">
            <h1>SKOOLKIT แพลตฟอร์มจัดการเรียนการสอนเเบบ Active Learning</h1>
            <h1>ที่รวบรวมทั้งสื่อเเละเครื่องมือไว้ในที่เดียวให้ได้ใช้งานฟรี</h1>
            <h3 class="font-weight-thin">
              เพียงลงทะเบียนฟอร์มด้านล่าง และรอการติดต่อกลับจากทีมงาน
            </h3>
          </div>
        </v-col>
      </v-container>
      <v-space></v-space>
      <v-container>
        <div class="text-center pb-7">
          <v-btn color="#DB2C27" large dark @click="$router.push('/trial')">
            <h3 class="font-weight-thin">ทดลองใช้งานฟรี</h3>
          </v-btn>
        </div>
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


