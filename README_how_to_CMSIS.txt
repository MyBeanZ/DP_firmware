README
jak nahrát CMSIS knihovnu: 
1) nutný include cesty k arm_math.h
2)přidat "arm_cortexM4lf_math" do knihovny v libraries, kdy ve skutečnosti GCC linker hledá lxxx.a (libarm_cortexM4lf_math.a)
3)přidat cestu ke knihovně