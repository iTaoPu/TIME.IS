function updateClock() {
    const now = new Date();
    
    // 获取时分秒，并确保两位数格式
    const hours = String(now.getHours()).padStart(2, '0');
    const minutes = String(now.getMinutes()).padStart(2, '0');
    const seconds = String(now.getSeconds()).padStart(2, '0');

    // 更新时间显示
    const timeDisplay = document.getElementById('time');
    timeDisplay.textContent = `${hours}:${minutes}:${seconds}`;

    // 更新日期（示例格式：2026年1月10日 星期六）
    const options = { year: 'numeric', month: 'long', day: 'numeric', weekday: 'long' };
    document.getElementById('date').textContent = now.toLocaleDateString('zh-CN', options);
}

// 每 100ms 检查一次，确保秒钟切换的流畅度（Time.is 实际上是与服务器同步，这里简化为本地时间）
setInterval(updateClock, 100);

// 初始化启动
updateClock();
