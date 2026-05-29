# my-super-minimalist-themes

Extensions I use: uBlock Origin, Enhancer for Youtube, SocialFocus, Unhook & Tubemod, Zen Internet (optional)
<hr>

## Table of Contents

**1.** [YouTube](#youtubeenhancer-for-youtube)

**2.** [**Ublock Origin: Twitter/Instagram/Reddit/YouTube**](https://github.com/Wisdawms/my-super-minimalist-themes#twitterinstagramreddityoutube-ublock-origin-filters)

**3.** [**Screenshots**](https://github.com/my-super-minimalist-themes#screenshots)





## YouTube (Enhancer for Youtube) 
After installing <a href="https://chromewebstore.google.com/detail/enhancer-for-youtube/ponfpcnoihfmfllpaingbgckeeldkhle">Enhancer for YouTube</a> extension, go to its settings and paste this code in the 'Custom Theme' box after checking it:

<pre>
  <code>
yt-animated-icon path,
#yt-logo-updated_yt5 path {
color: var(--main-text);
fill: var(--main-text);
}




#description {
background-color: var(--second-background) !important;
}
:root { --dimmer-text: #484054; --hover-background: #232225; --main-background: #121112; --main-color: #3e3847; --main-text: #725e4b; --second-background: #19191a; --shadow: 0 1px .5px rgba(23, 22, 23, .2);
}




*[role="text"]::selection{
    color: var(--main-text) !important;
    background-color: transparent !important;
}

/* --main-color: #3e3847*/



* {
font-family: 'nunito'; 
}

#yt-logo-updated-svg_yt3 path {
color: var(--main-text) !important;
}

#yt-logo-updated_yt3 g:first-child > path:nth-child(2) {
fill: var(--main-text) !important;
}

#voice-search-button {
display: none;
}
#search::placeholder{
color: var(--main-color) !important;
}
button:hover > * > * > * path{
transition: 0.5s fill ease;
}
/*

button:hover > * > * > * path{
fill: var(--main-color);
} */

#yt-logo-updated_yt1 path,
#toolbar path {
fill: var(--main-text);
}

#description.ytd-watch-metadata{
background: #19191a;
}
#input-container{
background-color: rgb(25, 25, 26) !important;
}

*[role="text"]{
color: var(--dimmer-text);
}

button > div> span[role="text"]{
color: var(--main-text);
}

.ytp-chrome-bottom * {
color: var(--main-text) !important;
fill: var(--main-text) !important;
}

.ytp-button .ytp-autonav-toggle-button-container {
display: none !important;
} 

.translate-button { 
color: var(--dimmer-text) !important;
}

#published-time-text > * { 
color: var(--dimmer-text) !important;
}

#content-text > * { 
color: var(--main-text);
}

#content-text > *::selection { 
background-color: var(--hover-background) !important;
}

span[class="yt-core-attributed-string--highlight-text-decorator"]{
background-color: var(--hover-background) !important;
}


[class="yt-spec-button-shape-next yt-spec-button-shape-next--text yt-spec-button-shape-next--mono yt-spec-button-shape-next--size-s"]:hover,
[class="yt-spec-button-shape-next yt-spec-button-shape-next--text yt-spec-button-shape-next--mono yt-spec-button-shape-next--size-s yt-spec-button-shape-next--icon-button yt-spec-button-shape-next--override-small-size-icon"]:hover {
background-color: var(--hover-background) !important;
}

.ytd-comment-engagement-bar
{
color: var(--dimmer-text) !important;
}

.ytd-text-inline-expander *
{
color: var(--main-text) !important;
}

.ytd-text-inline-expander a
{
color: var(--dimmer-text) !important;
}

/*a:hover
{
background-color: var(--hover-background) !important;
border-radius: 16px;
outline: 1px solid #CCC;
}*/

.ytSpecButtonShapeNextMono.ytSpecButtonShapeNextFilled
{
background-color: var(--second-background) !important;
}

.ytSpecIconShapeHost > div {
fill: var(--main-text) !important;
}

ytd-watch-metadata * {
color: var(--main-text) !important;
}

.ytContentMetadataViewModelMetadataRow {
color: var(--main-text) !important;
}

yt-formatted-string{
color: var(--main-text) !important;
}

.ytSpecButtonShapeNextButtonTextContent {
color: var(--main-text) !important;
}

#end.ytd-masthead{
min-width: 0 !important;
}

#content {
background: var(--main-background);
}

.video-stream {
left: 0 !important;
height: vh !important;
width: 100% !important;
}

  </code>
</pre>

## Ublock Origin: Twitter/Instagram/Reddit/YouTube<br>

<pre>
  <code>
!https://www.instagram.com
www.instagram.com##.x10rn61k.x1hfk2xs.x1k4gc0v.xb3f9ss.x1wfb79h.x19sv2k2.x106a9eq.x18d9i69.x1xnnf8n.x38y82z.x1ykew4q.xvc5jky.xat24cr.x11t971q.xdj266r.x1iyjqo2 > div:nth-of-type(2)
www.instagram.com##div:nth-of-type(7) > .x1n2onr6 > .x1qrby5j.x7ja8zs.x1t2pt76.x1lytzrv.xedcshv.xarpa2k.x3igimt.x12ejxvf.xaigb6o.x1beo9mf.xv2umb2.x1jfb8zj.x1h9r5lt.x1h91t0o.x4k7w5x.x1vvkbs.x16tdsg8.x1hl2dhg.x1c1uobl.x18d9i69.xyri2b.xexx8yu.x1lziwak.xat24cr.x14z9mp.xdj266r.html-span > .x1n2onr6 > ._a6hd.x4gyw5p.x1a2a7pz.xggy1nq.x1hl2dhg.x16tdsg8.x1c1uobl.x18d9i69.xyri2b.xexx8yu.x1lziwak.xat24cr.x14z9mp.xdj266r.xe8uvvx.xt0psk2.x1ypdohk.x9f619.x14e42zd.x1qhh985.x10w94by.x972fbf.xstzfhl.x1sy0etr.x18oe1m7.x1ejq31n.xjbqb8w.x1i10hfl > .x15x8krk.xde0f50.x5a5i1n.x1obq294.x1wj20lx.x1eunh74.x11hdxyr.x8st7rj.x9k3k5o.x1dejxi8.xdoji71.x10v4vz6.x1lhsz42.x4afuhf.x172qv1o.xif99yt.x1dn74xm.x159b3zp.x80pfx3.x1g0dm76.xsag5q8.xpdmqnj.xz9dl7a.x12dmmrz.x7nr27j.x6pnmvc.xo237n4.xjpr12u.xr9ek0c.x3nfvp2.x9f619
www.instagram.com##div:nth-of-type(4) > .x1qrby5j.x7ja8zs.x1t2pt76.x1lytzrv.xedcshv.xarpa2k.x3igimt.x12ejxvf.xaigb6o.x1beo9mf.xv2umb2.x1jfb8zj.x1h9r5lt.x1h91t0o.x4k7w5x.x1vvkbs.x16tdsg8.x1hl2dhg.x1c1uobl.x18d9i69.xyri2b.xexx8yu.x1lziwak.xat24cr.x14z9mp.xdj266r.html-span > .x1n2onr6 > ._a6hd.x4gyw5p.x1a2a7pz.xggy1nq.x1hl2dhg.x16tdsg8.x1c1uobl.x18d9i69.xyri2b.xexx8yu.x1lziwak.xat24cr.x14z9mp.xdj266r.xe8uvvx.xt0psk2.x1ypdohk.x9f619.x14e42zd.x1qhh985.x10w94by.x972fbf.xstzfhl.x1sy0etr.x18oe1m7.x1ejq31n.xjbqb8w.x1i10hfl > .x15x8krk.xde0f50.x5a5i1n.x1obq294.x1wj20lx.x1eunh74.x11hdxyr.x8st7rj.x9k3k5o.x1dejxi8.xdoji71.x10v4vz6.x1lhsz42.x4afuhf.x172qv1o.xif99yt.x1dn74xm.x159b3zp.x80pfx3.x1g0dm76.xsag5q8.xpdmqnj.xz9dl7a.x12dmmrz.x7nr27j.x6pnmvc.xo237n4.xjpr12u.xr9ek0c.x3nfvp2.x9f619
www.instagram.com##.xh8yej3.x1iyjqo2 > div:nth-of-type(3) > .x1qrby5j.x7ja8zs.x1t2pt76.x1lytzrv.xedcshv.xarpa2k.x3igimt.x12ejxvf.xaigb6o.x1beo9mf.xv2umb2.x1jfb8zj.x1h9r5lt.x1h91t0o.x4k7w5x.x1vvkbs.x16tdsg8.x1hl2dhg.x1c1uobl.x18d9i69.xyri2b.xexx8yu.x1lziwak.xat24cr.x14z9mp.xdj266r.html-span > .x1n2onr6 > ._a6hd.x4gyw5p.x1a2a7pz.xggy1nq.x1hl2dhg.x16tdsg8.x1c1uobl.x18d9i69.xyri2b.xexx8yu.x1lziwak.xat24cr.x14z9mp.xdj266r.xe8uvvx.xt0psk2.x1ypdohk.x9f619.x14e42zd.x1qhh985.x10w94by.x972fbf.xstzfhl.x1sy0etr.x18oe1m7.x1ejq31n.xjbqb8w.x1i10hfl > .x15x8krk.xde0f50.x5a5i1n.x1obq294.x1wj20lx.x1eunh74.x11hdxyr.x8st7rj.x9k3k5o.x1dejxi8.xdoji71.x10v4vz6.x1lhsz42.x4afuhf.x172qv1o.xif99yt.x1dn74xm.x159b3zp.x80pfx3.x1g0dm76.xsag5q8.xpdmqnj.xz9dl7a.x12dmmrz.x7nr27j.x6pnmvc.xo237n4.xjpr12u.xr9ek0c.x3nfvp2.x9f619
www.instagram.com##div:nth-of-type(2) > .x1qrby5j.x7ja8zs.x1t2pt76.x1lytzrv.xedcshv.xarpa2k.x3igimt.x12ejxvf.xaigb6o.x1beo9mf.xv2umb2.x1jfb8zj.x1h9r5lt.x1h91t0o.x4k7w5x.x1vvkbs.x16tdsg8.x1hl2dhg.x1c1uobl.x18d9i69.xyri2b.xexx8yu.x1lziwak.xat24cr.x14z9mp.xdj266r.html-span > .x1n2onr6 > ._a6hd.x4gyw5p.x1a2a7pz.xggy1nq.x1hl2dhg.x16tdsg8.x1c1uobl.x18d9i69.xyri2b.xexx8yu.x1lziwak.xat24cr.x14z9mp.xdj266r.xe8uvvx.xt0psk2.x1ypdohk.x9f619.x14e42zd.x1qhh985.x10w94by.x972fbf.xstzfhl.x1sy0etr.x18oe1m7.x1ejq31n.xjbqb8w.x1i10hfl > .x15x8krk.xde0f50.x5a5i1n.x1obq294.x1wj20lx.x1eunh74.x11hdxyr.x8st7rj.x9k3k5o.x1dejxi8.xdoji71.x10v4vz6.x1lhsz42.x4afuhf.x172qv1o.xif99yt.x1dn74xm.x159b3zp.x80pfx3.x1g0dm76.xsag5q8.xpdmqnj.xz9dl7a.x12dmmrz.x7nr27j.x6pnmvc.xo237n4.xjpr12u.xr9ek0c.x3nfvp2.x9f619
www.instagram.com##.x1azxncr > span.x1qrby5j.x7ja8zs.x1t2pt76.x1lytzrv.xedcshv.xarpa2k.x3igimt.x12ejxvf.xaigb6o.x1beo9mf.xv2umb2.x1jfb8zj.x1h9r5lt.x1h91t0o.x4k7w5x.x1vvkbs.x16tdsg8.x1hl2dhg.x1c1uobl.x18d9i69.xyri2b.xexx8yu.x1lziwak.xat24cr.x14z9mp.xdj266r.html-span:nth-of-type(1) > .x1n2onr6 > ._a6hd.x4gyw5p.x1a2a7pz.xggy1nq.x1hl2dhg.x16tdsg8.x1c1uobl.x18d9i69.xyri2b.xexx8yu.x1lziwak.xat24cr.x14z9mp.xdj266r.xe8uvvx.xt0psk2.x1ypdohk.x9f619.x14e42zd.x1qhh985.x10w94by.x972fbf.xstzfhl.x1sy0etr.x18oe1m7.x1ejq31n.xjbqb8w.x1i10hfl > .x15x8krk.xde0f50.x5a5i1n.x1obq294.x1wj20lx.x1eunh74.x11hdxyr.x8st7rj.x9k3k5o.x1dejxi8.xdoji71.x10v4vz6.x1lhsz42.x4afuhf.x172qv1o.xif99yt.x1dn74xm.x159b3zp.x80pfx3.x1g0dm76.xsag5q8.xpdmqnj.xz9dl7a.x12dmmrz.x7nr27j.x6pnmvc.xo237n4.xjpr12u.xr9ek0c.x3nfvp2.x9f619
www.instagram.com##.x1azxncr > div > .x1qrby5j.x7ja8zs.x1t2pt76.x1lytzrv.xedcshv.xarpa2k.x3igimt.x12ejxvf.xaigb6o.x1beo9mf.xv2umb2.x1jfb8zj.x1h9r5lt.x1h91t0o.x4k7w5x.x1vvkbs.x16tdsg8.x1hl2dhg.x1c1uobl.x18d9i69.xyri2b.xexx8yu.x1lziwak.xat24cr.x14z9mp.xdj266r.html-span > .x1n2onr6 > ._a6hd.x4gyw5p.x1a2a7pz.xggy1nq.x1hl2dhg.x16tdsg8.x1c1uobl.x18d9i69.xyri2b.xexx8yu.x1lziwak.xat24cr.x14z9mp.xdj266r.xe8uvvx.xt0psk2.x1ypdohk.x9f619.x14e42zd.x1qhh985.x10w94by.x972fbf.xstzfhl.x1sy0etr.x18oe1m7.x1ejq31n.xjbqb8w.x1i10hfl > .x15x8krk.xde0f50.x5a5i1n.x1obq294.x1wj20lx.x1eunh74.x11hdxyr.x8st7rj.x9k3k5o.x1dejxi8.xdoji71.x10v4vz6.x1lhsz42.x4afuhf.x172qv1o.xif99yt.x1dn74xm.x159b3zp.x80pfx3.x1g0dm76.xsag5q8.xpdmqnj.xz9dl7a.x12dmmrz.x7nr27j.x6pnmvc.xo237n4.xjpr12u.xr9ek0c.x3nfvp2.x9f619
www.instagram.com##span.x1qrby5j.x7ja8zs.x1t2pt76.x1lytzrv.xedcshv.xarpa2k.x3igimt.x12ejxvf.xaigb6o.x1beo9mf.xv2umb2.x1jfb8zj.x1h9r5lt.x1h91t0o.x4k7w5x.x1vvkbs.x16tdsg8.x1hl2dhg.x1c1uobl.x18d9i69.xyri2b.xexx8yu.x1lziwak.xat24cr.x14z9mp.xdj266r.html-span:nth-of-type(2) > .x1n2onr6 > ._a6hd.x4gyw5p.x1a2a7pz.xggy1nq.x1hl2dhg.x16tdsg8.x1c1uobl.x18d9i69.xyri2b.xexx8yu.x1lziwak.xat24cr.x14z9mp.xdj266r.xe8uvvx.xt0psk2.x1ypdohk.x9f619.x14e42zd.x1qhh985.x10w94by.x972fbf.xstzfhl.x1sy0etr.x18oe1m7.x1ejq31n.xjbqb8w.x1i10hfl > .x15x8krk.xde0f50.x5a5i1n.x1obq294.x1wj20lx.x1eunh74.x11hdxyr.x8st7rj.x9k3k5o.x1dejxi8.xdoji71.x10v4vz6.x1lhsz42.x4afuhf.x172qv1o.xif99yt.x1dn74xm.x159b3zp.x80pfx3.x1g0dm76.xsag5q8.xpdmqnj.xz9dl7a.x12dmmrz.x7nr27j.x6pnmvc.xo237n4.xjpr12u.xr9ek0c.x3nfvp2.x9f619
www.instagram.com##.x1nhvcw1.x1oa3qoh.x6s0dn4.xqjyukv.xdt5ytf.x2lah0s.x1c4vz4f.xryxfnj.x1plvlek.x1uhb9sk.xbiv7yw.x16uus16.x1ga7v0g.x15mokao.x78zum5.xjbqb8w.x9f619.x1c1uobl.x18d9i69.xyri2b.xexx8yu.x1lziwak.xat24cr.x14z9mp.xdj266r.html-div
www.instagram.com##.xfk6m8.x7coems.xwib8y2.xrw5ot4.x1y1aw1k.x78zum5.x1rohswg.x1n2onr6.x10wlt62.xw2csxc.x5yr21d.x1q0g3np.x1qjc9v5
www.instagram.com##.x1nhvcw1.x1oa3qoh.x1qjc9v5.xqjyukv.xdt5ytf.x2lah0s.x1c4vz4f.xryxfnj.x1plvlek.x1uhb9sk.xseo6mj.xbiv7yw.x16uus16.x1ga7v0g.x15mokao.x78zum5.xjbqb8w.x9f619.x1c1uobl.x18d9i69.xyri2b.xexx8yu.x1lziwak.xat24cr.x14z9mp.html-div
www.instagram.com##.xixxii4.x145d82y.x3h4tne.x1nhvcw1.x1oa3qoh.x1qjc9v5.xqjyukv.xdt5ytf.x2lah0s.x1c4vz4f.xryxfnj.x1plvlek.xbiv7yw.x16uus16.x1ga7v0g.x15mokao.x78zum5.xjbqb8w.x9f619.x1c1uobl.x18d9i69.xyri2b.xexx8yu.x1lziwak.xat24cr.x14z9mp.xdj266r.html-div
www.instagram.com##.x135b78x.xf159sx.x1qughib.x1oa3qoh.x6s0dn4.xqjyukv.x1q0g3np.x2lah0s.x1c4vz4f.xryxfnj.x1plvlek.x1uhb9sk.x1y1aw1k.xwib8y2.xbiv7yw.x16uus16.x1ga7v0g.x15mokao.x78zum5.xjbqb8w.x1f5funs.x9f619.x1lziwak.xat24cr.x14z9mp.xdj266r.html-div
www.instagram.com##.x1nhvcw1.x1oa3qoh.x1qjc9v5.xqjyukv.x1q0g3np.xeuugli.x2lwn1j.x1iyjqo2.xryxfnj.x1plvlek.x1uhb9sk.xbiv7yw.x16uus16.x1ga7v0g.x15mokao.x78zum5.xjbqb8w.x9f619.x1c1uobl.x18d9i69.xyri2b.xexx8yu.x1lziwak.xat24cr.x14z9mp.xdj266r.html-div > .x1n2onr6.x10wlt62.x6ikm8r.x1nhvcw1.x1oa3qoh.x1qjc9v5.xqjyukv.xdt5ytf.xeuugli.x2lwn1j.x1iyjqo2.xbiv7yw.x16uus16.x1ga7v0g.x15mokao.x78zum5.xjbqb8w.x9f619.x1c1uobl.x18d9i69.xyri2b.xexx8yu.x1lziwak.xat24cr.x14z9mp.xdj266r.html-div
www.instagram.com##.x1n2onr6 > .x1qrby5j.x7ja8zs.x1t2pt76.x1lytzrv.xedcshv.xarpa2k.x3igimt.x12ejxvf.xaigb6o.x1beo9mf.xv2umb2.x1jfb8zj.x1h9r5lt.x1h91t0o.x4k7w5x.x1vvkbs.x16tdsg8.x1hl2dhg.x1c1uobl.x18d9i69.xyri2b.xexx8yu.x1lziwak.xat24cr.x14z9mp.xdj266r.html-span > .x1n2onr6
www.instagram.com##.xh8yej3.x1iyjqo2 > div > .x1qrby5j.x7ja8zs.x1t2pt76.x1lytzrv.xedcshv.xarpa2k.x3igimt.x12ejxvf.xaigb6o.x1beo9mf.xv2umb2.x1jfb8zj.x1h9r5lt.x1h91t0o.x4k7w5x.x1vvkbs.x16tdsg8.x1hl2dhg.x1c1uobl.x18d9i69.xyri2b.xexx8yu.x1lziwak.xat24cr.x14z9mp.xdj266r.html-span > .x1n2onr6
www.instagram.com##.x1vjfegm.xixxii4.x10wlt62.x6ikm8r.xtpu1e1.x1ve1609.x1wp8tw6.x1y0lptx.x1mg3h75.x7vuprf.x1a5l9x9.x6nl9eh.x7r02ix.x1nhvcw1.x1oa3qoh.x1qjc9v5.xqjyukv.xdt5ytf.x2lah0s.x1c4vz4f.x78zum5.x5lhr3w.x16ye13r.x9f619.x1c1uobl.x18d9i69.xyri2b.xexx8yu.x1lziwak.xat24cr.x14z9mp.xdj266r.html-div

! https://x.com
x.com##.r-1loqt21.r-1xc7w19.r-cgjvx2.r-j3xhw6.r-st84sj.css-175oi2r > .r-136ojw6.r-1h3ijdo.css-175oi2r
x.com##.r-y42jk5.r-1jte41z.r-hvns9x.r-1rtiivn.r-173mn98.css-175oi2r
x.com##.r-ttdzmv.r-vacyoi.css-175oi2r
x.com##a.r-1loqt21.r-1ny4l3l.r-13qz1uu.r-cnw61z.r-1habvwh.r-16y2uox.r-eqz5dr.r-6koalj.css-175oi2r:nth-of-type(8) > .r-6416eg.r-o7ynqc.r-xyw6el.r-1777fci.r-18u37iz.r-1awozwy.r-dnmrzs.r-sdzlij.css-175oi2r
x.com##a.r-1loqt21.r-1ny4l3l.r-13qz1uu.r-cnw61z.r-1habvwh.r-16y2uox.r-eqz5dr.r-6koalj.css-175oi2r:nth-of-type(4) > .r-6416eg.r-o7ynqc.r-xyw6el.r-1777fci.r-18u37iz.r-1awozwy.r-dnmrzs.r-sdzlij.css-175oi2r
x.com##.r-1ye8kvj.r-13qz1uu.r-f8sm7e.r-1lg4w6u.r-1abdc3e.r-184en5c.r-16y2uox.r-1phboty.r-th6na.r-1ua6aaf.r-1kqtdi0.r-kemksi.css-175oi2r
x.com##div.r-12vffkv.css-175oi2r:nth-of-type(1) > .r-12vffkv.css-175oi2r > .r-bnwqim.r-1va2g9v.r-6gpygo.r-173mn98.r-633pao.css-175oi2r > .r-1ny4l3l.r-6416eg.r-o7ynqc.r-1loqt21.r-1tfmumk.r-u8s1d.r-1777fci.r-8oi148.r-qo02w8.r-rs99b7.r-1867qdf.r-j7xza8.r-5zmot.r-1e5uvyk.r-173mn98.r-1awozwy.r-105ug2t.css-175oi2r
x.com##.r-bnwqim.r-1va2g9v.r-6gpygo.r-1euycsn.r-6koalj.r-173mn98.r-633pao.css-175oi2r > .r-1ny4l3l.r-6416eg.r-o7ynqc.r-1loqt21.r-1tfmumk.r-u8s1d.r-1777fci.r-8oi148.r-qo02w8.r-rs99b7.r-1867qdf.r-j7xza8.r-5zmot.r-1e5uvyk.r-173mn98.r-1awozwy.r-105ug2t.css-175oi2r
x.com##div.r-16y2uox.r-cpa5s6.r-14tvyh0.css-175oi2r:nth-of-type(1) > .r-1ny4l3l.r-6416eg.r-o7ynqc.r-1loqt21.r-3pj75a.r-s8bhmr.r-1777fci.r-1h3ijdo.r-16y2uox.r-eqz5dr.r-6koalj.r-1awozwy.css-175oi2r
x.com##div.r-16y2uox.r-cpa5s6.r-14tvyh0.css-175oi2r:nth-of-type(1)

!https://www.reddit.com
www.reddit.com###flex-nav-expand-button > .justify-center.items-center.flex > .flex > svg
www.reddit.com###flex-nav-expand-button
www.reddit.com##.border-e-neutral-border.s\:border-e-sm.border-solid.border-0.m\:block.hidden.order-first.isolate.theme-rpl.left-sidebar
www.reddit.com##.bg-tone-2
www.reddit.com##.bg-tone-4
www.reddit.com##.my-2xs.py-2xs.px-md.flex-col.flex.nd\:visible
www.reddit.com##hr.border-b-neutral-border-weak.border-solid.border-b-sm.border-0:nth-of-type(2)

! https://www.twitch.tv
www.twitch.tv##.iDMNUO.InjectLayout-sc-1i43xsx-0 > .yezmM.ScCoreButton-sc-ocjdkq-0
www.twitch.tv##div.VxLcr.Layout-sc-1xcs6mc-0 > .ihSefD.Layout-sc-1xcs6mc-0 > .iDMNUO.InjectLayout-sc-1i43xsx-0 > .Layout-sc-1xcs6mc-0 > .fHdBNk.Layout-sc-1xcs6mc-0 > .kOoFSj.Layout-sc-1xcs6mc-0 > .tw-new-item-indicator__container.lbpZbS.ScNewItemIndicatorWrapper-sc-1udtibe-2 > .bplIQq.ScNewItemIndicator-sc-1udtibe-0
www.twitch.tv##.gWaIYG.Layout-sc-1xcs6mc-0 > .ihSefD.Layout-sc-1xcs6mc-0 > .iDMNUO.InjectLayout-sc-1i43xsx-0 > .Layout-sc-1xcs6mc-0 > .fHdBNk.Layout-sc-1xcs6mc-0 > .kOoFSj.Layout-sc-1xcs6mc-0 > .tw-new-item-indicator__container.lbpZbS.ScNewItemIndicatorWrapper-sc-1udtibe-2 > .bplIQq.ScNewItemIndicator-sc-1udtibe-0
www.twitch.tv##div.side-nav-section.iGMbNn.Layout-sc-1xcs6mc-0:nth-of-type(4)

! https://www.youtube.com
www.youtube.com###secondary

  </code>
</pre> <br>

<h2>Screenshots</h2>

<h3>YouTube</h3>
<img width="1920" height="4116" alt="Screenshot 2026-05-30 at 00-18-24 Blonde Redhead - Kiss Her Kiss Her (Live on KEXP) - YouTube" src="https://github.com/user-attachments/assets/d5b4be5d-1177-4ecd-b836-b8fba5506999" />
<img width="1904" height="1016" alt="image" src="https://github.com/user-attachments/assets/4b1939fe-5e26-4bcf-9a9e-4eea364684a7" />

<h3>Twitter</h3>
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/05d2146d-aa41-45d4-88ab-2145200b314f" />

<h3>Instagram</h3>
<img width="1920" height="3364" alt="image" src="https://github.com/user-attachments/assets/7822ca24-cfd6-4403-abb3-ed2fb98179d3" />
<img width="1904" height="1016" alt="image" src="https://github.com/user-attachments/assets/358d6239-136b-40d0-8c13-0ad1c4bd60c5" />


<h3>Reddit</h3>
<img width="1920" height="2782" alt="image" src="https://github.com/user-attachments/assets/a0072772-9e0f-4b18-986d-95ef88dfb631" />

