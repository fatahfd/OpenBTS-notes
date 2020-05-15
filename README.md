# OpenBTS-notes
🇮🇩  install @kali-linux kernel 4.x.x
> installasi openbts pada ubuntu > 16 dan kali,  serasa seperti berton-ton besi di kepala

## OpenBTS install

### Basic Installation
ikuti instruksi om Onno
http://onnocenter.or.id/wiki/index.php/OpenBTS:_Build_OpenBTS_5.0_di_Ubuntu_16.04_32bit

### error pada libcoredumper

> remark libcoredumper pada build.sh
> gunakan alternative https://github.com/tom-2015/fakecoredumper

### error macro "gettid"
> remark deklarasi gettid di commonlibs/Logger.h ~~(I dont know what i'm doing but it works :) )~~

### error  a53.h not found
> make install pada liba53

### error  Please specify the compatibility level in debian/compat
> create file debian/compat, isi file dengan magic word  "9" 
> echo "9" > debian/compat
