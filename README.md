docker 安装遇到404错误，从docker容器日志看是esbuild service 异常终止
ERROR in 85733.6fefa6b1f33a2828ba5f.min.js
85733.6fefa6b1f33a2828ba5f.min.js from Terser plugin
The service was stopped
Error: The service was stopped
    at /usr/src/app/node_modules/esbuild/lib/main.js:737:38
    at responseCallbacks.<computed> (/usr/src/app/node_modules/esbuild/lib/main.js:622:9)
    at Socket.afterClose (/usr/src/app/node_modules/esbuild/lib/main.js:613:28)webpack 5.97.1 compiled with 63 errors in 11107 ms
    at Socket.emit (node:events:536:35)
    at endReadableNT (node:internal/streams/readable:1698:12)
    at process.processTicksAndRejections (node:internal/process/task_queues:90:21)
