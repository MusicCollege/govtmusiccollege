<!DOCTYPE html>
<html lang="hi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>शासकीय संगीत महाविद्यालय, मंदसौर</title>

<style>
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background: #fafafa;
    color: #222;
}

/* Header */
header {
    background: #7a0909;
    color: white;
    padding: 20px;
    text-align: center;
}
header h1 {
    margin: 0;
    font-size: 26px;
    font-weight: 700;
}
header h2 {
    margin-top: 6px;
    font-size: 15px;
    opacity: 0.9;
}

/* Section Cards */
section {
    padding: 20px;
}
.card {
    background: white;
    padding: 18px;
    border-radius: 12px;
    max-width: 900px;
    margin: auto;
    box-shadow: 0 2px 6px rgba(0,0,0,0.15);
}

h2 {
    font-size: 22px;
    color: #7a0909;
}

.small { font-size: 14px; opacity: 0.7; }

/* Courses*/
ul { padding-left: 18px; }

/* Grid Layout */
.grid {
    display: grid;
    gap: 12px;
}
@media(min-width:700px){
    .grid {
        grid-template-columns: 1fr 1fr;
    }
}

/* Contact Form */
label { font-size: 14px; }
input, textarea {
    width: 100%;
    padding: 8px;
    margin-top: 5px;
    border-radius: 6px;
    border: 1px solid #bbb;
}
button {
    background: #7a0909;
    color: white;
    border: none;
    padding: 10px 18px;
    border-radius: 6px;
    cursor: pointer;
}

/* Gallery Grid */
.gallery {
    display: grid;
    gap: 12px;
}
.gallery img {
    width: 100%;
    border-radius: 10px;
}

/* Footer */
footer {
    background: #333;
    color: white;
    padding: 20px;
    margin-top: 30px;
}
footer .small { opacity: 0.8; }
</style>
</head>

<body>

<header>
    <h1>शासकीय संगीत महाविद्यालय, मंदसौर</h1>
    <h2>Affiliated With राजा मानसिंह तोमर संगीत एवं कला विश्वविद्यालय, ग्वालियर</h2>
</header>

<section id="about">
<div class="card">
<h2>About the College</h2>
<p>
<strong>शासकीय संगीत महाविद्यालय, मंदसौर</strong> भारत की समृद्ध संगीत एवं कला परंपरा को संरक्षित करने, सिखाने और आगे बढ़ाने के उद्देश्य से कार्यरत है।
यहाँ विद्यार्थियों को शास्त्रीय एवं समकालीन संगीत की व्यवस्थित एवं विशेषज्ञ शिक्षण पद्धति प्रदान की जाती है।
</p>
</div>
</section>

<section id="courses">
<div class="card">
<h2>Courses Offered / पाठ्यक्रम</h2>
<ul>
<li>1. प्रवेशिका – Certificate in Performing Arts</li>
<li>2. मध्यमा – Diploma in Performing Arts</li>
<li>3. विद – Diploma in Performing Arts</li>
<li>4. बैचलर इन परफॉर्मिंग आर्ट्स (प्रथम)</li>
<li>5. मास्टर ऑफ परफॉर्मिंग आर्ट्स</li>
</ul>
<p class="small">अधिक जानकारी के लिए कॉलेज कार्यालय से संपर्क करें।</p>
</div>
</section>

<section id="admission">
<div class="card">
<h2>Admission / प्रवेश</h2>
<p>इच्छुक विद्यार्थी आवेदन पत्र कार्यालय से प्राप्त कर सकते हैं या ईमेल द्वारा मंगवा सकते हैं।</p>

<div class="grid">
<div>
<h3>How to Apply</h3>
<ol>
<li>आवेदन पत्र प्राप्त करें</li>
<li>आवश्यक दस्तावेज़ लगाकर जमा करें</li>
<li>ऑडिशन/प्रवेश परीक्षा (यदि लागू हो)</li>
</ol>
</div>

<div>
<h3>Documents Required</h3>
<ul>
<li>10वीं/12वीं मार्कशीट</li>
<li>फोटो</li>
<li>आईडी प्रूफ</li>
<li>म्यूज़िक सर्टिफिकेट (यदि हों)</li>
</ul>
</div>
</div>
</div>
</section>

<section id="gallery">
<div class="card">
<h2>Gallery</h2>
<div class="gallery">
<img src="DSC_1045.JPG">
<img src="DSC_1166.JPG">
<img src="DSC_1172.jpg">
</div>
</div>
</section>

<section id="contact">
<div class="card">
<h2>Contact / संपर्क</h2>

<div class="grid">
<div>
<p><strong>Address:</strong> Government Music College, Ramtekri Corner, Mandsaur – 458001</p>
<p><strong>Email:</strong> Govtmusiccollagemds@gmail.com</p>
<p><strong>Phone:</strong> 07422 245202</p>
</div>

<div>
<form onsubmit="event.preventDefault(); alert('Your message has been received (demo).');">
<label>Name</label>
<input required>

<label>Email</label>
<input type="email" required>

<label>Message</label>
<textarea rows="4" required></textarea>

<button type="submit">Send</button>
</form>
</div>
</div>
</div>
</section>

<footer>
<div style="max-width:900px;margin:auto;">
<div>© शासकीय संगीत महाविद्यालय, मंदसौर</div>
<div class="small">Affiliated With राजा मानसिंह तोमर संगीत एवं कला विश्वविद्यालय, ग्वालियर</div>
</div>
</footer>

</body>
</html>
