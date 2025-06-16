<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Surprise!</title>
<style>
  body {
    font-family: 'Arial', sans-serif;
    background-color: #f7f7f7;
    text-align: center;
    padding: 50px;
  }
  h1 {
    color: #333;
    margin-bottom: 20px;
  }
  p {
    color: #555;
    font-size: 18px;
  }
  button {
    background-color: #4CAF50;
    color: white;
    padding: 14px 20px;
    margin: 20px 0;
    border: none;
    cursor: pointer;
    font-size: 18px;
  }
  button:hover {
    background-color: #45a049;
  }
  .hiddenContent {
    display: none;
    color: #333;
    background-color: #fff;
    border: 1px solid #ddd;
    padding: 20px;
    margin-top: 20px;
  }
</style>
<script>
function toggleContent(contentId) {
  var content = document.getElementById(contentId);
  if (content.style.display === "none") {
    content.style.display = "block";
  } else {
    content.style.display = "none";
  }
}
</script>
</head>
<body>

<h1>Haha</h1>
<p>မင်းနာမည် ထက်အာကာဖြိုး မလား? 😄 မရှက်ပါနဲ့။ အောက်က Button တွေနှိပ်ကြည့် 👇👇.</p>
<button onclick="toggleContent('content1')">စော်လိုချင်တယ်</button>
<div id="content1" class="hiddenContent">
<p>အိမ်မက်မက်ပြီး စိတ်ကူးတွေယဉ်မနေနဲ့ အိပ်ယာက နိုးတော့ 🔔🔔🔔</p>
</div>
<button onclick="toggleContent('content2')">စိတ်ဆိုးနေပြီလား?</button>
<div id="content2" class="hiddenContent">
<p>ငါတကယ်တောင်းပန်ပါတယ်ကွာ နောက်ဒါမျိုးမလုပ်တော့ပါဘူး လို့ပြောမယ်ထင်နေလား? မပြောပါဘူး</p>
</div>
<button onclick="toggleContent('content3')">မနှိပ်နဲ့</button>
<div id="content3" class="hiddenContent">
<p>မနှိပ်နဲ့လို့ပြောတာတောင် လီးမို့နှိပ်တာလား 😂😂</p>
</div>
<button onclick="toggleContent('content4')">လျှာထုတ်ပြီး အသက်ရှူကြည့်</button>
<div id="content4" class="hiddenContent">
<p>သေချာရှူကြည့်ပါ၊ မိုက်တယ်</p>
</div>
<button onclick="toggleContent('content5')">ဘာနဲ့တူလဲသိလား</button>
<div id="content5" class="hiddenContent">
<p>ကျောင်းရောက်ရင် ပြောပြမယ်။</p>
</div>

</body>
</html>
