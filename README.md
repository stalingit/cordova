# cordova
This is cordova code admob android
using follwing plugin
https://github.com/ratson/cordova-plugin-admob-free

 public void onBackPressed() {

        Intent intent = new Intent(Main2Activity.this,
                MainActivity.class);
        intent.setFlags(Intent.FLAG_ACTIVITY_CLEAR_TOP
                | Intent.FLAG_ACTIVITY_SINGLE_TOP);
        startActivity(intent);
    }
