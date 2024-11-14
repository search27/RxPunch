# RxPunch

Support By [ Cloud Rx (<a href='https://rxapis.com'>https://rxapis.com</a>) ].
* Testing is available until 2025/12/31 23:59.

<img width="1677" alt="스크린샷 2024-11-14 오후 12 04 44" src="https://github.com/user-attachments/assets/1c040905-d647-4678-830f-47a14e8ad70b">
<img width="1677" alt="스크린샷 2024-11-14 오후 12 04 34" src="https://github.com/user-attachments/assets/df82ad5b-5466-4f68-b4eb-ee6f0e6688f8">
<img width="1677" alt="스크린샷 2024-11-14 오후 12 04 51" src="https://github.com/user-attachments/assets/746152d8-22f2-4a45-8942-9f4b95a085a9">



```javascript
const logo = new Image();
logo.src = './rx_apis_logo3.png';

const image = new Image();
image.src = BASE64;

image.addEventListener('load', function(){
    punch = new RxPunch({
        text : 'Loading...',        // Text
        fontSize : 53,              // Font Size
        punchCount : 10,            // Punch Count Per 1 count
        // startImage : 'white',    // CoverImage Or Color <String>
        startImage : logo,
        position : 'center',        // Inside Image Position
        scale : 1,                  // Inside Image Scale
        image : this,               // Inside Image
        ele : document.getElementById('circle'),    // Target Element
        duration : 10 * 1000,                       // Execution Duration
    });
});

```
