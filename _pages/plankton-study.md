---
title: DEAL Plankton Study
layout: page
permalink: /plankton-study/
redirect_to: /plankton-study-2/
redirect_delay: 15
description: 
---

You have probably landed on this page from a link to my previous
[Generated Plankton Study](/plankton-study-2/). You will be redirected to the current
version in <span id="timer">15</span> seconds. If the redirect doesn't happen
automatically, follow the [link](/plankton-study-2/).

<script>
  document.addEventListener("DOMContentLoaded", function () {
    var timerEl = document.getElementById("timer");
    if (!timerEl) {
      return;
    }
    var seconds = 15;
    var interval = setInterval(function () {
      seconds -= 1;
      if (seconds <= 0) {
        clearInterval(interval);
        return;
      }
      timerEl.textContent = seconds;
    }, 1000);
  });
</script>
