# iOS_tip

https://blog.kakaocdn.net/dn/JenGg/btq4bYE0yD6/78I0FBSsGoKCB1MDkklRZ1/img.gif
UIApplication.shared.perform(#selector(NSXPCConnection.suspend)) 
DispatchQueue.main.asyncAfter(deadline: .now() + 0.5) { exit(0) ✅ }
