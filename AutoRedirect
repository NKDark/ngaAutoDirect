// ==UserScript==
// @name         自动跳转
// @namespace    http://tampermonkey.net/
// @version      0.1
// @description  try to take over the world!
// @author       You
// @match        https://bbs.nga.cn/*
// @grant        none
// ==/UserScript==

(function() {
    'use strict';
    var url = window.location.href
    var sub = url.substr(url.indexOf(".cn/")+4);
    window.location.replace("https://nga.178.com/"+sub);
})();
