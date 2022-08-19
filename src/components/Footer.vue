<script setup>
import { ref } from 'vue';

const date = ref();
date.value = new Date().getFullYear();
</script>

<template>
    <footer>
        <div class="fixed bottom-0 text-center left-0 right-0 p-5 text-zinc-500 font-light text-sm">
            <span>
                Copyright © {{ date }}
                <a class="hover:underline hover:underline-offset-1" href="https://zzlz.gsxt.gov.cn/businessCheck/viewPdfImage?licence13=92350212MA8W1WFW01" target="_blank">厦门市同安区辞寒网络工作室</a>
                版权所有
            </span>
        </div>
    </footer>
</template>