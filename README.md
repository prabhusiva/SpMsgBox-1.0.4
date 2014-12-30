SpMsgBox-1.0.4
==============

Customized Model Message Box for Web Applications

### Welcome to SPMsgBox.
 
The SpMsgBox plugin is useful for all Web Applications. you can customize what you like. u just want to include
the jquery and Style sheet with images. it is easiest one for display a alert messages in your Web Applications.

 You can Customize the dialog what you like!..  <br>
 
For More options see Demo http://www.prabhusiva.in/2014/12/jmsgbox-examples.html  <br>
Simply add in your web page in any event.. <br>
### Syntax: <br>
### For Show <br>
```
$.SPMsgBox.Show("Message","Title");
```

### For ShowSuccess <br>
```
$.SPMsgBox.ShowSuccess("Message","Title");
```

### For ShowError <br>
```
$.SPMsgBox.ShowError("Message","Title");
```

### For ShowWarning <br>
```
$.SPMsgBox.ShowWarning("Message","Title");
```

### For ShowInfo <br>
```
$.SPMsgBox.ShowInfo("Message","Title");
```

### Options <br>
Use  $.SPMsgBox.options={}; for Setting all the Options for Your Page <br>
Use Options in Layout page Or in Each Page for setting the properties what you like <br>

```
$.SPMsgBox.options = {
"autoHide": false,
"progressBar": true,
"hideCloseIcon": false,
"position": "top-right"
"stayTime": "3000",
"inEffectDuration": "600",
"bkColor1": "#1c95eb",
"bkColor2": "#6c899e",
"pBarColor": "#b5f507",
"Msg": "You like this Dialog"
};
```

 ### Dependencies : <br>
 You have to use the Jquery script (above 1.11.11 versions) <br>

