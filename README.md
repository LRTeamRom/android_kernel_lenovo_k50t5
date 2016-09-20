# android_kernel_lenovo_k50t5

==============================


* Build Kernel (./kernel-3.10 folder):

* Command:

    sudo chmod -R 777 * ~/android_kernel_lenovo_k50t5/aarch64-linux-android-4.9/bin/
    
    cd ~/android_kernel_lenovo_k50t5/kernel-3.10

    PATH=${PATH}:~/android_kernel_lenovo_k50t5/aarch64-linux-android-4.9/bin/

    export ARCH=arm64

    make aio_5m_defconfig ARCH=arm64 CROSS_COMPILE=aarch64-linux-android-

    make ARCH=arm64 CROSS_COMPILE=aarch64-linux-android-


==============================
