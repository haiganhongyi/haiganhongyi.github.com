---
layout: default
title: 首页 
---
<div id="rain-drops">
    <hgroup class="ignore">
        <h2>假如，生活欺骗了你</h2>
        <p>-- 普希金 --</p>
    </hgroup>
    <p>假如/生活欺骗了你，</p>
    <p>不要/悲伤，不要/心急!</p>
    <p>忧郁的/日子里需要镇静：</p>
    <p>相信吧，快乐的/日子/将会/来临。</p>
    <p>心儿/永远/向往着/未来；</p>
    <p>现在/却常是/忧郁。</p>
    <p>一切/都是/瞬息，</p>
    <p>一切/都将会/过去；</p>
    <p>而那/过去了的，</p>
    <p>就会成为/亲切的/怀恋。</p>
</div>
<script src="/assets/js/jquery.min.js"></script>
<script src="/assets/js/writePoetry.min.js></script>
<script>
var wp = $.writePoetry('#rain-drops', {ignoreClass: '.ignore'});
wp.appendData('<p>Test it is ok?</p>');
</script>
