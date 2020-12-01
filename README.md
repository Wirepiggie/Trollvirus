Set WshShell = WScript.CreateObject ("WScript.Shell")

strName = wshShell.ExpandEnvironmentStrings ("% USERNAME%")

x = msgbox ("Are you sure you would like to continue?", 4 + 16, "Warning!")

if x = 6 Then

msgbox "You Have Successfully Started Download", 0 + 64, "Success!"

WScript.sleep 200

msgbox "Would You Like Abort Download", 4 + 16, "VIRUS DETECTED!"

wshshell.Run "cmd"

WScript.sleep 200

wshshell.sendkeys "exit"

wshshell.sendkeys "{ENTER}"

wshshell.Run "cmd"

WScript.sleep 200

wshshell.sendkeys "exit"

wshshell.sendkeys "{ENTER}"

wshshell.Run "cmd"

WScript.sleep 200

wshshell.sendkeys "exit"

wshshell.sendkeys "{ENTER}"

wshshell.Run "cmd"

WScript.sleep 200

wshshell.sendkeys "exit"

wshshell.sendkeys "{ENTER}"

wshshell.Run "cmd"

WScript.sleep 200

wshshell.sendkeys "exit"

wshshell.sendkeys "{ENTER}"

wshshell.Run "cmd"

WScript.sleep 200

wshshell.sendkeys "exit"

wshshell.sendkeys "{ENTER}"

y = msgbox ("Unable To Abort Download, Would you like to retry?", 4 + 16,"Error")

If y = 6 Then

wshshell.Run "cmd"

WScript.sleep 200

wshshell.sendkeys "exit"

wshshell.sendkeys "{ENTER}"

wshshell.Run "cmd"

WScript.sleep 200

wshshell.sendkeys "exit"

wshshell.sendkeys "{ENTER}"

wshshell.Run "cmd"

WScript.sleep 200

wshshell.sendkeys "exit"

wshshell.sendkeys "{ENTER}"

wshshell.Run "cmd"

WScript.sleep 200

wshshell.sendkeys "exit"

wshshell.sendkeys "{ENTER}"

wshshell.Run "cmd"

WScript.sleep 200

wshshell.sendkeys "exit"

wshshell.sendkeys "{ENTER}"

wshshell.Run "cmd"

WScript.sleep 

wshshell.sendkeys "exit"

wshshell.sendkeys "{ENTER}"

msgbox "Unable To Abort", 0 + 16,"ERROR"

End If

If y = 7 Then

msgbox "Hi"

msgbox "Hi"

msgbox "Hi"

msgbox "Hi"

msgbox "Hi"

msgbox "Hi"

msgbox "Hi"

msgbox "Hi"

msgbox "Hi"

msgbox "Hi"

msgbox "Hi"

msgbox "Hi"

msgbox "Hi"

msgbox "Hi"

msgbox "Hi"

msgbox "Hi"

msgbox "Hi"

msgbox "Hi"

msgbox "Hi"

msgbox "Hi"

End
