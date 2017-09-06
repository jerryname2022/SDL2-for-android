# SDL2-for-android
# 工程目录：
            SDL2-2.0.5
                        ./Android.mk                       --⑶
                        ./android-project
                                    ./jni
                                    ./src/Android.mk       --⑴
                                    ./Android.mk           --⑵
                                    ./Application.mk
                                    
</p>
--⑶ Android.mk 用来编译SDL2-2.0.5工程的mk文件，里面写好了编译代码。可以编译出(SDL2)静态或者动态库。</p>
--⑵ Android.mk 用来编译android-project工程的mk文件。可以编译出(main)的动态库。</p>
--⑴ Android.mk 用来编译src下自己写的代码的编译文件。</p>

