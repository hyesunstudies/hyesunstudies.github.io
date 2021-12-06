---
layout: default
---

<script type="application/javascript">

function resizeIFrameToFitContent( iFrame ) {

    iFrame.width  = iFrame.contentWindow.document.body.scrollWidth;
    iFrame.height = iFrame.contentWindow.document.body.scrollHeight;
}

window.addEventListener('DOMContentLoaded', function(e) {

    var iFrame = document.getElementById( 'iFrame1' );
    resizeIFrameToFitContent( iFrame );

    // or, to resize all iframes:
    var iframes = document.querySelectorAll("iframe");
    for( var i = 0; i < iframes.length; i++) {
        resizeIFrameToFitContent( iframes[i] );
    }
} );

</script>

<span style="font-size: 22px;"><b>[Bài 1: Tiêu đề bài 1](./posts/post_001.html)</b></span>
<span style="font-size: 12px;">&nbsp;&nbsp; _Dec 4, 2021 bởi <a href="https://www.facebook.com/hoang.huyen.332" target="_blank">Hoàng Huyền</a>_</span>

> tóm tắt nội dung bài 1.........

tóm tắt nội dung bài 1.........

<iframe frameBorder="0" id="iFrame1"
  src="https://www.youtube.com/embed/hxmUjXXTmpU">
</iframe>

<!-- <iframe width="300" height="230" frameBorder="0"
  src="https://www.youtube.com/embed/hxmUjXXTmpU">
</iframe> -->
<br/><br/>

<!-- # Bài 2
---
<small>- _Dec 4, 2021 by <a href="https://www.facebook.com/hoang.huyen.332" target="_blank">Hoàng Huyền</a>_</small> -->
<span style="font-size: 22px;"><b>[Bài 2: Tiêu đề bài 2](./posts/post_002.html)</b></span>
<span style="font-size: 12px;">&nbsp;&nbsp; _Dec 4, 2021 bởi <a href="https://www.facebook.com/hoang.huyen.332" target="_blank">Hoàng Huyền</a>_</span>

> tóm tắt nội dung bài 2...

Text here...