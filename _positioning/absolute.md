---
layout: default
title: Absolute positioning
description: Lorem ipsum
short_example_dom: >
    <div class='absolute-positioning-wrapper'>
        <div class='absolute-positioning-elem'></div>
    </div>
short_example_scss: >
    .absolute-positioning-wrapper {
        background-color: white;
        height: 100%;
        width: 100%;
        position: relative;

        .absolute-positioning-elem {
            background-color: red;
            position: absolute;
            height: 10px;
            width: 10px;
            bottom: 3px;
            right: 3px;
        }
    }
---

Winter is coming