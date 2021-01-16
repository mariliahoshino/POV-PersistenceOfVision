# POV-PersistenceOfVision
DIY project POV-PersistenceOfVision


How to change a code the program in AT89S52 for Shack Stick Persistence of Vision


<img src="https://github.com/mariliahoshino/Shake_Stick_POV-PersistenceOfVision/blob/main/picture/20201216_214225.jpg?raw=true" height="400" widht="400" > &nbsp;&nbsp;&nbsp;<img src="https://github.com/mariliahoshino/Shake_Stick_POV-PersistenceOfVision/blob/main/picture/20201216_214733.jpg?raw=true" height="400" widht="400" > <br>

<img src="https://github.com/mariliahoshino/Shake_Stick_POV-PersistenceOfVision/blob/main/picture/20201216_231614.jpg?raw=true" height="400" widht="400" > &nbsp;&nbsp;&nbsp;<img src="https://github.com/mariliahoshino/Shake_Stick_POV-PersistenceOfVision/blob/main/picture/20201216_231623.jpg?raw=true" height="400" widht="400" > <br>

<img src="https://github.com/mariliahoshino/mariliahoshino/blob/master/School/logo_senac.png?raw=true" height="30" widht="400" >
<img src="https://github.com/mariliahoshino/mariliahoshino/blob/master/School/logo_senac.png?raw=true" height="30" widht="400" ><br>


<!--
<embed src="https://render.githubusercontent.com/view/pdf?color_mode=dark&amp;commit=78b32d31a60ac4eeae04e5869425596d696ad7d4&amp;enc_url=68747470733a2f2f7261772e67697468756275736572636f6e74656e742e636f6d2f6d6172696c6961686f7368696e6f2f5368616b655f537469636b5f504f562d50657273697374656e63654f66566973696f6e2f373862333264333161363061633465656165303465353836393432353539366436393661643764342f706963747572652f504f562d537469636b5f536368656d617469632e706466&amp;nwo=mariliahoshino%2FShake_Stick_POV-PersistenceOfVision&amp;path=picture%2FPOV-Stick_Schematic.pdf&amp;repository_id=327756317&amp;repository_type=Repository#f11713e4-f83f-4abf-b56d-d6728612344e"> 
<link rel="canonical" href="https://render.githubusercontent.com/view/pdf?color_mode=dark&amp;commit=78b32d31a60ac4eeae04e5869425596d696ad7d4&amp;enc_url=68747470733a2f2f7261772e67697468756275736572636f6e74656e742e636f6d2f6d6172696c6961686f7368696e6f2f5368616b655f537469636b5f504f562d50657273697374656e63654f66566973696f6e2f373862333264333161363061633465656165303465353836393432353539366436393661643764342f706963747572652f504f562d537469636b5f536368656d617469632e706466&amp;nwo=mariliahoshino%2FShake_Stick_POV-PersistenceOfVision&amp;path=picture%2FPOV-Stick_Schematic.pdf&amp;repository_id=327756317&amp;repository_type=Repository#f11713e4-f83f-4abf-b56d-d6728612344e" data-pjax-transient>
<include-fragment src="https://render.githubusercontent.com/view/pdf?color_mode=dark&amp;commit=78b32d31a60ac4eeae04e5869425596d696ad7d4&amp;enc_url=68747470733a2f2f7261772e67697468756275736572636f6e74656e742e636f6d2f6d6172696c6961686f7368696e6f2f5368616b655f537469636b5f504f562d50657273697374656e63654f66566973696f6e2f373862333264333161363061633465656165303465353836393432353539366436393661643764342f706963747572652f504f562d537469636b5f536368656d617469632e706466&amp;nwo=mariliahoshino%2FShake_Stick_POV-PersistenceOfVision&amp;path=picture%2FPOV-Stick_Schematic.pdf&amp;repository_id=327756317&amp;repository_type=Repository#f11713e4-f83f-4abf-b56d-d6728612344e" class="commit-loader">
  
  
  -->
  
  
  <iframe src="https://render.githubusercontent.com/view/pdf?color_mode=dark&amp;commit=78b32d31a60ac4eeae04e5869425596d696ad7d4&amp;enc_url=68747470733a2f2f7261772e67697468756275736572636f6e74656e742e636f6d2f6d6172696c6961686f7368696e6f2f5368616b655f537469636b5f504f562d50657273697374656e63654f66566973696f6e2f373862333264333161363061633465656165303465353836393432353539366436393661643764342f706963747572652f504f562d537469636b5f536368656d617469632e706466&amp;nwo=mariliahoshino%2FShake_Stick_POV-PersistenceOfVision&amp;path=picture%2FPOV-Stick_Schematic.pdf&amp;repository_id=327756317&amp;repository_type=Repository#f11713e4-f83f-4abf-b56d-d6728612344e" width="600" height="780" style="border: none;"></iframe>
  
  
  <table cellpadding="0" cellspacing="0" align="center" width="100%" height="100%">
<tr>
<td><iframe src="https://render.githubusercontent.com/view/pdf?color_mode=dark&amp;commit=78b32d31a60ac4eeae04e5869425596d696ad7d4&amp;enc_url=68747470733a2f2f7261772e67697468756275736572636f6e74656e742e636f6d2f6d6172696c6961686f7368696e6f2f5368616b655f537469636b5f504f562d50657273697374656e63654f66566973696f6e2f373862333264333161363061633465656165303465353836393432353539366436393661643764342f706963747572652f504f562d537469636b5f536368656d617469632e706466&amp;nwo=mariliahoshino%2FShake_Stick_POV-PersistenceOfVision&amp;path=picture%2FPOV-Stick_Schematic.pdf&amp;repository_id=327756317&amp;repository_type=Repository#f11713e4-f83f-4abf-b56d-d6728612344e" width="600" height="780" style="border: none;"></iframe></td>
<td><iframe src=https://github.com/mariliahoshino/Shake_Stick_POV-PersistenceOfVision/blob/main/picture/POV-Stick_Schematic.pdf width="600" height="780" style="border: none;"></iframe></td>
</tr>
  
  
  
  
  <div class="render-wrapper ">
    <div class="render-container is-render-pending js-render-target  "
      data-identity="f11713e4-f83f-4abf-b56d-d6728612344e"
      data-host="https://render.githubusercontent.com"
      data-type="pdf">
      <svg viewBox="0 0 16 16" fill="none" style="box-sizing: content-box; color: var(--color-icon-primary);" class="octospinner mx-auto" width="64" height="64">
  <circle cx="8" cy="8" r="7" stroke="currentColor" stroke-opacity="0.25" stroke-width="2" vector-effect="non-scaling-stroke" />
  <path d="M15 8a7.002 7.002 0 00-7-7" stroke="currentColor" stroke-width="2" stroke-linecap="round" vector-effect="non-scaling-stroke">
    <animateTransform attributeName="transform" type="rotate" from="0 8 8" to="360 8 8" dur="1s" repeatCount="indefinite" />
  </path>
</svg>
      <div class="render-viewer-error">Sorry, something went wrong. <a href="https://github.com/mariliahoshino/Shake_Stick_POV-PersistenceOfVision/blob/main/picture/POV-Stick_Schematic.pdf">Reload?</a></div>
      <div class="render-viewer-fatal">Sorry, we cannot display this file.</div>
      <div class="render-viewer-invalid">Sorry, this file is invalid so it cannot be displayed.</div>
      <iframe class="render-viewer " src="https://render.githubusercontent.com/view/pdf?color_mode=dark&amp;commit=78b32d31a60ac4eeae04e5869425596d696ad7d4&amp;enc_url=68747470733a2f2f7261772e67697468756275736572636f6e74656e742e636f6d2f6d6172696c6961686f7368696e6f2f5368616b655f537469636b5f504f562d50657273697374656e63654f66566973696f6e2f373862333264333161363061633465656165303465353836393432353539366436393661643764342f706963747572652f504f562d537469636b5f536368656d617469632e706466&amp;nwo=mariliahoshino%2FShake_Stick_POV-PersistenceOfVision&amp;path=picture%2FPOV-Stick_Schematic.pdf&amp;repository_id=327756317&amp;repository_type=Repository#f11713e4-f83f-4abf-b56d-d6728612344e" sandbox="allow-scripts allow-same-origin allow-top-navigation" title="File display">
          Viewer requires iframe.
      </iframe>
    </div>
  
  
  
  
  
  
  
  



### My Degree

<a href="https://www.sp.senac.br/">   <img src="https://github.com/mariliahoshino/mariliahoshino/blob/master/School/logo_senac.png?raw=true" height="30" widht="400" > </a> &nbsp;Post graduation Quality of Software Engineering 

<a href="http://www.umc.br/">    <img src="https://github.com/mariliahoshino/mariliahoshino/blob/master/School/logo_umc.png?raw=true" height="30" widht="400"></a>  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Bachelor Electric Engineering UMC  

<a href="https://eletronica.sp.senai.br/"> <img src="https://github.com/mariliahoshino/mariliahoshino/blob/master/School/logo_senai.png?raw=true" height="30" widht="400"></a>  &nbsp;&nbsp;&nbsp; Electronic Technical SENAI - Anchieta  

<a href="https://www.cps.sp.gov.br/tag/etec-presidente-vargas/">  <img src="https://github.com/mariliahoshino/mariliahoshino/blob/master/School/logo_etec.png?raw=true" height="30" widht="400"> </a> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Mechatronics Technical ETEC Presidente Vargas 

<a href="https://suzano.sp.senai.br/"> <img src="https://github.com/mariliahoshino/mariliahoshino/blob/master/School/logo_senai.png?raw=true" height="30" widht="400"></a>  &nbsp;&nbsp;&nbsp; Maintenance Electrical SENAI - Suzano  

### My profile in 

<a href="https://www.linkedin.com/in/mariliahoshino/"><img src="https://github.com/mariliahoshino/mariliahoshino/blob/master/profile/logo_linkedin.png?raw=true" height="20" widht="400"></a> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 
<a href="https://mariliahoshino.wixsite.com/cvitae/"> Personal page <img src ="https://github.com/mariliahoshino/mariliahoshino/blob/master/profile/logo_site.png?raw=true" height="20" widht="400"></a> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 
<a href="https://www.instagram.com/mari.zeniti/"><img src = "https://github.com/mariliahoshino/mariliahoshino/blob/master/profile/logo_instagram.png?raw=true"  height="20" widht="400"></a> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 
<a href="https://www.facebook.com/mari.zeniti"><img src="https://github.com/mariliahoshino/mariliahoshino/blob/master/profile/logo_facebook.png?raw=true"   height="20" widht="400"></a>






Source:<br><br>
How program AVR<br>
https://www.youtube.com/watch?v=EKlpHcpSUzQ <br>

Program for burn AVR<br>
https://github.com/elementzonline/USBASP-8051/blob/master/PROGISP1.72.zip <br>

Program for edit code<br>
https://mikroc-pro-for-8051.software.informer.com/download/#downloading <br>

Or Can use this for edit code<br>
https://www.keil.com/demo/eval/c51.htm#/DOWNLOAD <br>

https://leap.tardate.com/electronics101/povshakestickkit/

https://pan.baidu.com/share/link?shareid=532839&uk=1161248057

https://goughlui.com/2016/11/21/project-at89s52-based-led-shake-stick-kit/

https://goughlui.com/2016/11/22/hack-customize-the-led-shake-stick-images/
