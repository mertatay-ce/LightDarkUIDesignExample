# LightDarkUIDesignExample
Android UI tasarımı üzerinde **Light ve Dark Mode** çalışması

Bu projede Android alanında light ve dark modunda UI tasarımının nasıl olduğu gerçekleştirilmiştir. Kodlama aşamasında kullanılan dosyalar şunlardır:

-> <a href='https://github.com/mertatay-ce/LightDarkUIDesignExample/tree/main/app/src/main/res'>Resources (Dosyalar)</a> <br>
-> <a href='https://github.com/mertatay-ce/LightDarkUIDesignExample/tree/main/app/src/main/res/layout'>Pencereler (Light Mode)</a> <br>
-> <a href='https://github.com/mertatay-ce/LightDarkUIDesignExample/tree/main/app/src/main/res/layout-night'>Pencereler (Dark Mode)</a> <br>

Kullanılan framework çerçevelerine aşağıdan ulaşabilirsiniz. 

-> <a href='https://github.com/mertatay-ce/LightDarkUIDesignExample/blob/main/app/build.gradle'>app/Build.gradle</a> <br>
-> <a href='https://github.com/mertatay-ce/LightDarkUIDesignExample/blob/main/build.gradle'>main/Build.gradle</a>

Projede emulatör kullanma sırasında emulatörün dark mode ayarına göre default olarak değişimi sağlanmakta. Kod ile uğraşmadan dark mode tasarımı konusunda emulator veya canlıya alınan bir cihaz üzerinde ilgili cihazın dark modunun açıp kapatarak değişimi çıktı olarak elde edebilirsiniz.<br>

Projede, ***res/drawable-night*** <br> ***res/color-night*** <br> ***res/styles-night*** gibi sonu klasör ismi ..-night ile biten klasörlerinde bulunan dosyalar dark modda çalışan dosyalardır.

***res/drawable*** <br> ***res/styles*** <br> ***res/color*** <br> gibi sonu klasör ismiyle biten klasörler light modda çalışan dosyalardır.<br>

**Not:** Yapı olarak CoordinatorLayout ve BottomNavigationView componentleri içermektedir.<br>

Çıktı olarak:<br>

https://user-images.githubusercontent.com/79770837/207956082-aa88c02e-6f5e-4263-af0a-cb9b6c4b7d54.mov

Resim çıktısı:
<div>
<img src='https://github.com/mertatay-ce/LightDarkUIDesignExample/blob/main/darkmode_output.png' width='300' height='700' />
<img src='https://github.com/mertatay-ce/LightDarkUIDesignExample/blob/main/lightmode_output.png' width='300' height='700' />
</div>
