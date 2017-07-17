# Android-How-to-Download-and-Make-Volley.jar
If you are using Android Studio then how to add volley.jar at your project.
Adding volley support can done just by adding ‘compile com.mcxiaoke.volley:library-aar:1.0.0‘ to gradle.build dependencies module.

dependencies {
compile fileTree(dir: 'libs', include: ['*.jar'])
compile 'com.android.support:appcompat-v7:22.2.0'
 
compile 'com.mcxiaoke.volley:library-aar:1.0.0'
}
