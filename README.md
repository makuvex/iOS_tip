# iOS_tip

1. 앱을 💕⭐️💚❤️예쁘게⭐️❤️☀️💙💕종료시키기

출처: https://zeddios.tistory.com/1252 [ZeddiOS]

UIApplication.shared.perform(#selector(NSXPCConnection.suspend)) 

DispatchQueue.main.asyncAfter(deadline: .now() + 0.5) { 

    exit(0) ✅ 
  
}

<img src="https://blog.kakaocdn.net/dn/JenGg/btq4bYE0yD6/78I0FBSsGoKCB1MDkklRZ1/img.gif" srcset="https://blog.kakaocdn.net/dn/JenGg/btq4bYE0yD6/78I0FBSsGoKCB1MDkklRZ1/img.gif" data-filename="ezgif.com-video-to-gif-5.gif" data-origin-width="600" data-origin-height="1090" data-ke-mobilestyle="widthContent">

