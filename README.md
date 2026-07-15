---
layout: default
title: Data Integration
---

<link href="https://fonts.googleapis.com/css2?family=Sarabun:wght@300;400;500&family=Mitr:wght@300;400;500&display=swap" rel="stylesheet">

<style>
* { margin: 0; padding: 0; box-sizing: border-box; }

body {
  font-family: 'Sarabun', sans-serif;
  background: #fff0f5;
  color: #4a1030;
}

body::before {
  content: '';
  position: fixed;
  inset: 0;
  background-image: radial-gradient(circle, #f9a8be 1.5px, transparent 1.5px);
  background-size: 28px 28px;
  opacity: 0.25;
  pointer-events: none;
  z-index: 0;
}

.wrap { position: relative; z-index: 1; }

.ribbon {
  background: #f9a8be;
  text-align: center;
  padding: 5px;
  font-size: 13px;
  letter-spacing: 6px;
  color: white;
  box-shadow: 0 2px 0 #f48aaa;
}

.page-header {
  background: #e8557a;
  padding: 1rem 2rem;
  box-shadow: 0 3px 0 #c03060;
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.page-header .logo {
  font-family: 'Mitr', sans-serif;
  font-size: 1.05rem;
  color: white;
}

.page-header a {
  color: white;
  text-decoration: none;
  font-size: 0.88rem;
  background: rgba(255,255,255,0.2);
  padding: 4px 14px;
  border-radius: 20px;
}

main {
  max-width: 720px;
  margin: 2rem auto;
  padding: 0 1.5rem 4rem;
}

.hero-card {
  background: white;
  border-radius: 24px;
  border: 2px solid #f9a8be;
  padding: 2rem 2rem 1.5rem;
  margin-bottom: 1.5rem;
  box-shadow: 0 6px 0 #f4c0ce;
  text-align: center;
}

.kw-num {
  font-size: 11px;
  font-weight: 500;
  letter-spacing: .12em;
  color: #f9a8be;
  margin-bottom: 6px;
  font-family: 'Mitr', sans-serif;
}

.kw-title {
  font-family: 'Mitr', sans-serif;
  font-size: 2rem;
  font-weight: 500;
  color: #c0304a;
  margin-bottom: 8px;
}

.kw-badge {
  display: inline-block;
  background: #e8557a;
  color: white;
  font-size: 12px;
  padding: 3px 14px;
  border-radius: 20px;
  font-family: 'Mitr', sans-serif;
}

.card {
  background: white;
  border-radius: 20px;
  border: 1.5px solid #f9c8d8;
  padding: 1.6rem 1.8rem;
  margin-bottom: 1.2rem;
  box-shadow: 0 4px 0 #f4c0ce;
}

.section-title {
  font-family: 'Mitr', sans-serif;
  font-size: 0.98rem;
  color: #c0304a;
  margin-bottom: 1rem;
  padding-bottom: 0.6rem;
  border-bottom: 2px dashed #f9c8d8;
  display: flex;
  align-items: center;
  gap: 8px;
}

.badge {
  background: #e8557a;
  color: white;
  font-size: 11px;
  padding: 2px 10px;
  border-radius: 20px;
  font-family: 'Mitr', sans-serif;
}

blockquote {
  border-left: 3px solid #e8557a;
  padding: 0.75rem 1rem;
  margin: 0.75rem 0;
  background: #fff5f8;
  border-radius: 0 12px 12px 0;
  color: #6b2840;
  font-size: 0.93rem;
  line-height: 1.8;
}

blockquote em { color: #c0304a; font-style: normal; font-weight: 500; }

.thai-box {
  background: #fff5f8;
  border: 1.5px dashed #f9a8be;
  border-radius: 16px;
  padding: 1rem 1.2rem;
  color: #6b2840;
  font-size: 0.93rem;
  line-height: 1.9;
}

table { width: 100%; border-collapse: collapse; font-size: 0.91rem; }
th {
  background: #e8557a;
  color: white;
  padding: 9px 14px;
  text-align: left;
  font-family: 'Mitr', sans-serif;
  font-weight: 400;
}
th:first-child { border-radius: 10px 0 0 0; }
th:last-child  { border-radius: 0 10px 0 0; }
td { padding: 9px 14px; border-bottom: 1px solid #fce0ea; color: #6b2840; }
tr:last-child td { border-bottom: none; }
tr:nth-child(even) td { background: #fff5f8; }

.ai-block {
  border: 1.5px solid #f9c8d8;
  border-radius: 16px;
  padding: 1rem 1.2rem;
  margin-bottom: 0.8rem;
  background: #fff5f8;
}
.ai-block p { font-size: 0.93rem; line-height: 1.8; color: #6b2840; }
.ai-src { font-size: 11px; color: #e8557a; margin-top: 6px; font-weight: 500; }

.refs-list { list-style: none; display: flex; flex-direction: column; gap: 8px; }
.refs-list li { font-size: 0.91rem; color: #6b2840; }
.refs-list a { color: #c0304a; text-decoration: none; }
.refs-list a:hover { text-decoration: underline; }

.back-link {
  display: inline-block;
  margin-top: 1.5rem;
  background: #e8557a;
  color: white;
  text-decoration: none;
  padding: 8px 22px;
  border-radius: 20px;
  font-family: 'Mitr', sans-serif;
  font-size: 0.9rem;
  box-shadow: 0 3px 0 #c03060;
}

footer {
  background: #e8557a;
  color: white;
  text-align: center;
  padding: 1rem;
  font-size: 0.83rem;
  letter-spacing: 0.06em;
  box-shadow: 0 -3px 0 #c03060;
}
</style>

<div class="wrap">

<div class="page-header">
  <div class="logo">🎀 sximi.github.io</div>
  <a href="https://sximi.github.io">← หน้าหลัก</a>
</div>
<div class="ribbon">🌸 ✿ 🎀 ✿ 🌸 ✿ 🎀 ✿ 🌸 ✿ 🎀 ✿ 🌸</div>

<main>

  <div class="hero-card">
    <div class="kw-num">KEYWORD 04</div>
    <div class="kw-title">🔗 Data Integration</div>
    <span class="kw-badge">Data & Analytics</span>
  </div>

  <div class="card">
    <div class="section-title">📖 Definition <span class="badge">English</span></div>
    <blockquote>
      "Data integration is the process of combining data from different sources into a single, unified view. Integration begins with the ingestion process and includes steps such as cleansing, ETL mapping, and transformation."
      <br><br><em>— IBM</em>
    </blockquote>
    <blockquote>
      "Data integration involves combining data residing in different sources and providing users with a unified view of these data. This process becomes significant in a variety of situations, which include both commercial and scientific domains."
      <br><br><em>— Oracle</em>
    </blockquote>
  </div>

  <div class="card">
    <div class="section-title">🇹🇭 คำนิยาม <span class="badge">Thai</span></div>
    <div class="thai-box">
      Data Integration คือ <strong>"การรวมข้อมูลจากหลายที่ให้เป็นหนึ่งเดียว"</strong> — เหมือนเอาวัตถุดิบจากหลายร้านมาทำอาหารจานเดียวกัน ข้อมูลจาก Database, API, ไฟล์ Excel หรือ IoT จะถูกดึงมารวมกัน เพื่อให้วิเคราะห์ได้อย่างครบถ้วนและแม่นยำ 🌸
    </div>
  </div>

  <div class="card">
    <div class="section-title">🔍 Explanation <span class="badge">ขยายความ</span></div>
    <table>
      <tr><th>ขั้นตอน ETL</th><th>ความหมาย</th><th>ตัวอย่าง</th></tr>
      <tr><td>🔵 Extract</td><td>ดึงข้อมูลจากแหล่งต้นทาง</td><td>Database, API, CSV</td></tr>
      <tr><td>🟡 Transform</td><td>แปลงและทำความสะอาด</td><td>แก้ format, กรอง null</td></tr>
      <tr><td>🟢 Load</td><td>โหลดเข้า destination</td><td>Data Warehouse</td></tr>
    </table>
    <br>
    <table>
      <tr><th>รูปแบบ</th><th>วิธีการ</th></tr>
      <tr><td><strong>ETL</strong></td><td>Extract → Transform → Load (batch)</td></tr>
      <tr><td><strong>ELT</strong></td><td>Extract → Load → Transform (cloud)</td></tr>
      <tr><td><strong>Real-time</strong></td><td>รับข้อมูลแบบ streaming เช่น Kafka</td></tr>
      <tr><td><strong>API Integration</strong></td><td>เชื่อมต่อผ่าน API ระหว่าง service</td></tr>
    </table>
  </div>

  <div class="card">
    <div class="section-title">🤖 GenAI Explanation</div>
    <div class="ai-block">
      <p>"Data Integration คือหัวใจของการทำ Data Analytics — ถ้าข้อมูลอยู่กระจัดกระจายก็ไม่สามารถเห็นภาพรวมได้ เหมือนพยายามต่อจิ๊กซอว์โดยไม่มีชิ้นส่วนครบ"</p>
      <div class="ai-src">— ChatGPT (OpenAI)</div>
    </div>
    <div class="ai-block">
      <p>"ในยุคที่ข้อมูลมาจากหลายแพลตฟอร์ม Data Integration จึงเป็นทักษะที่สำคัญมาก องค์กรที่รวมข้อมูลได้ดีจะตัดสินใจได้เร็วและแม่นยำกว่าคู่แข่ง"</p>
      <div class="ai-src">— Gemini (Google)</div>
    </div>
  </div>

  <div class="card">
    <div class="section-title">📚 References</div>
    <ul class="refs-list">
      <li>1. IBM. (2024). <a href="https://www.ibm.com/topics/data-integration"><em>What is Data Integration?</em></a></li>
      <li>2. Oracle. (2024). <a href="https://www.oracle.com/integration/what-is-data-integration/"><em>Data Integration</em></a></li>
      <li>3. Microsoft. (2024). <a href="https://learn.microsoft.com/en-us/azure/architecture/data-guide/relational-data/etl"><em>Data integration in Azure</em></a></li>
    </ul>
  </div>

  <a class="back-link" href="https://sximi.github.io">🎀 กลับหน้าหลัก</a>

</main>

<footer>🎀 made with ♡ · จันทรัสม์ เต็มทอง · My Melody Theme 🌸</footer>

</div>
