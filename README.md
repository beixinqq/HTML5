# HTML5
HTML5
  第五章：跨文档消息通信
    postMessage对象
        1.接收消息的窗口对象postMessage()
        2.一参 : 发送的数据，二参 : 发送的域
        3.交互方式
            1.iframe：父页面 : contentWindow、子页面 : window.top
            2.窗口页: 父页面 : window.open、子页面 : window.opener
        4.接收事件：
            1.message
            2.ev.origin : 发送数据来源的域
            3.ev.data : 发送的数据
