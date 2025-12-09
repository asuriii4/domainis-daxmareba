# domainis-daxmareba
<!DOCTYPE html>
<html lang="ka">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>აბრამოვიჩის ფონდი</title>
<style>
/* General Styles */
body {
    font-family: 'Segoe UI', Arial, sans-serif;
    margin: 0;
    padding: 0;
    background: #f0f7ff;
    color: #333;
}

header {
    background: url('https://i.ibb.co/Q7wwLZS8/psd-charity-humanity-community-care-flyer-poster-banner-1232774-313.jpg') center/cover no-repeat;
    position: relative;
    height: 400px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
    color: white;
}
header::before {
    content: '';
    position: absolute;
    top:0; left:0;
    width:100%; height:100%;
    background: rgba(0,0,0,0.5);
    z-index:1;
}
header img {
    width: 160px;
    margin-bottom: 15px;
    position: relative;
    z-index:2;
}
header h1, header p {
    margin: 5px 0;
    position: relative;
    z-index:2;
}
header h1 { font-size:36px; }
header p { font-size:18px; }

/* Section Styles */
section {
    max-width: 950px;
    margin: 40px auto;
    background: white;
    padding: 40px;
    border-radius: 12px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.08);
}
h2, h3 { color: #1a365d; }
ul { line-height: 1.8; }

.donation-box {
    background: #eaf4ff;
    border-left: 5px solid #4a90e2;
    padding: 25px;
    border-radius: 10px;
    margin-top: 20px;
}
.donation-box p { margin: 5px 0; font-size:16px; }

.newsletter {
    margin-top: 40px;
    padding: 30px;
    background: #eaf9f0;
    border-radius: 12px;
    border: 1px solid #cfeece;
    text-align: center;
}
input[type="email"] {
    padding: 14px;
    width: 70%;
    border: 1px solid #b5b5b5;
    border-radius: 8px;
    margin-right: 10px;
    font-size: 16px;
}
button {
    padding: 14px 24px;
    background: #2b6cb0;
    color: white;
    border: none;
    border-radius: 8px;
    cursor: pointer;
    font-size: 16px;
    transition: 0.3s;
}
button:hover { background: #234e85; }

footer {
    text-align: center;
    padding: 25px;
    margin-top: 40px;
    color: #666;
    font-size: 14px;
}

/* Slider */
.slider-container {
    width: 100%;
    overflow: hidden;
    margin: 40px auto;
    padding: 20px 0;
    background: #ffffff;
    border-radius: 14px;
    box-shadow: 0 3px 12px rgba(0,0,0,0.12);
}
.slider-track {
    display: flex;
    width: calc(300px * 8);
    animation: scroll 20s linear infinite;
}
.slider-track img {
    width: 300px;
    height: 220px;
    object-fit: cover;
    border-radius: 12px;
    margin-right: 20px;
    box-shadow: 0 2px 6px rgba(0,0,0,0.2);
}
@keyframes scroll {
    0% { transform: translateX(0); }
    100% { transform: translateX(-50%); }
}
.slider-title { text-align:center; font-size:28px; color:#1a365d; }

/* Accordion FAQ */
.accordion {
    background-color: #eaf4ff;
    color: #1a365d;
    cursor: pointer;
    padding: 15px 20px;
    width: 100%;
    border: none;
    text-align: left;
    outline: none;
    font-size: 18px;
    border-radius: 8px;
    margin-top: 12px;
    transition: 0.3s;
}
.accordion.active { background-color: #d4e8ff; }
.panel {
    background-color: white;
    overflow: hidden;
    max-height: 0;
    transition: max-height 0.4s ease;
    padding: 0 20px;
    border-left: 3px solid #4a90e2;
    margin-bottom: 10px;
}
.panel p { padding: 15px 0; margin:0; }

/* Responsive */
@media(max-width:768px) {
    .slider-track img { width:240px; height:180px; }
    input[type="email"] { width:100%; margin-bottom:10px; }
    button { width:100%; }
}
</style>
</head>
<body>

<header>
    <img src="https://i.ibb.co/Kcy7myjr/Screenshot-2025-12-08-051233-removebg-preview.webp" alt="Abramovich Fund Logo">
    <h1>აბრამოვიჩის ფონდი</h1>
    <p>დავეხმაროთ იმ ადამიანებს, ვისაც სჭირდებათ ფინანსური დახმარება</p>
</header>

<section>
    <h2>რას ვაკეთებთ</h2>
    <p>
        აბრამოვიჩის ფონდი ეხმარება მათ, ვისაც სჭირდება სწრაფი ფინანსური მხარდაჭერა მძიმე დაავადებების, ინვალიდობის ან სხვა სამედიცინო საჭიროებების შემთხვევაში.
ჩვენ ვგროვობთ საჭირო თანხებს მათთვის, ვისაც არა აქვს რესურსი ძვირადღირებული ოპერაციებისთვის ან მკურნალობისთვის, და ვგზავნით პირდაპირ მათ, რათა მიეცეთ შესაძლებლობა მიიღონ საჭირო დახმარება.
ჩვენ ვთანამშრომლობთ ბავშვებთან, ადამიანებთან, რომელთაც აქვთ ქრონიკული ან დამანგრეველი დაავადებები, და ოჯახებთან, რომლებიც სიღარიბის ან სხვა კრიზისული მდგომარეობის გამო ვერ უზრუნველყოფენ საჭირო სამედიცინო მოვლას. ჩვენი მიზანია იმედი და მხარდაჭერა მივაწოდოთ მათ, როცა ყველაზე მეტად სჭირდებათ.
    </p>
    <h3>ჩვენი მიზანი</h3>
    <ul>
        <li>💙 ბავშვების მხარდაჭერა, ვისაც კიბოსა და სიცოცხლისთვის საფრთხის შემცველი დაავადებები აქვთ</li>
        <li>🤝 დახმარება სიღარიბისგან დაზარალებულ ოჯახებს</li>
        <li>🌍 გადაუდებელი სამედიცინო დახმარების დაფინანსება</li>
        <li>✨ იმედის მინიჭება მათთვის, ვისაც სჭირდება</li>
    </ul>
</section>

<section>
    <h2 class="slider-title">ადამიანები, ვისაც თქვენი დახმარება სჭირდება</h2>
    <div class="slider-container">
        <div class="slider-track">
            <img src="https://tvmonitoringi.ge/public/image_base/2/2025-05-06/1746518899_780X480_22222222222222222222222222222222222.png">
            <img src="https://megatv.ge/wp-content/uploads/2023/07/%E1%83%A2%E1%83%90%E1%83%98-%E1%83%90%E1%83%A0%E1%83%90%E1%83%91%E1%83%A3%E1%83%9A%E1%83%98.png">
            <img src="https://primetime.ge/uploads/files/2023/06/13/54716/nikoloz-chachibaia_w_h.jpeg">
            <img src="https://primetime.ge/uploads/files/2022/12/19/35275/nikolozi_w_h.jpeg">
            <!-- Repeat for continuous scroll -->
            <img src="https://tvmonitoringi.ge/public/image_base/2/2025-05-06/1746518899_780X480_22222222222222222222222222222222222.png">
            <img src="https://megatv.ge/wp-content/uploads/2023/07/%E1%83%A2%E1%83%90%E1%83%98-%E1%83%90%E1%83%A0%E1%83%90%E1%83%91%E1%83%A3%E1%83%9A%E1%83%98.png">
            <img src="https://primetime.ge/uploads/files/2023/06/13/54716/nikoloz-chachibaia_w_h.jpeg">
            <img src="https://primetime.ge/uploads/files/2022/12/19/35275/nikolozi_w_h.jpeg">
        </div>
    </div>
</section>

<section>
    <div class="donation-box">
        <h3>❤️ სიცოცხლის დასახსნელად</h3>
        <p>თუ გსურთ დაგვეხმაროთ პირდაპირ, შეგიძლიათ დარიცხოთ ჩვენს ბანკში:</p>
        <p><strong>Georgia Bank</strong></p>
        <p><strong>საიდენტიფიკაციო ნომერი:</strong> 01256004223</p>
        <p><strong>IBAN:</strong> GE32BG0000000539948309</p>
    </div>

    <div class="newsletter">
        <h3>გამოიწერეთ ჩვენი არხი</h3>
        <p>მიიღეთ ინფორმაცია იმ ადამიანების შესახებ, ვისაც ვეხმარებით.</p>
        <form id="newsletterForm">
            <input type="email" id="emailInput" placeholder="შეიყვანეთ თქვენი იმეილი" required>
            <button type="submit">გამოწერა</button>
        </form>
    </div>
</section>

<section>
    <h2>შეკითხვები</h2>
    <button class="accordion">აბრამოვიჩის ფონდი დამეხმარება თუ არა?</button>
    <div class="panel"><p>დიახ, დაგვიკავშირდით ცხელხაზზე რათა გაესაუბროთ მხარდაჭერის წევრს ამ საკითხე.</p></div>

    <button class="accordion">ნამდვილი ორგანიზაცია ხართ?</button>
    <div class="panel"><p>ჩვენი ფონდი არის ვერიფიცირებული სხვადასხვა არასამთავრობო ჯგუფების მიერ.</p></div>

    <button class="accordion">სად მიდის შემოწირული თანხები?</button>
    <div class="panel"><p>ფინანსები ინახება ჩვენს კომპანიის ვალუტში და გადაერიცხება საჭირო პირებს.</p></div>

    <button class="accordion">ვინ არის ორგანიზაციის მფლობელი?</button>
    <div class="panel"><p>ორგანიზაცია შექმნილია დიმიტრი აბრამოვიჩის, რუსო-უკრაინელი ბიზნესმენის მიერ.</p></div>
</section>

<section>
    <h2>კონტაქტი</h2>
    <p><strong>ტელეფონი:</strong> (995+) 574-801-451</p>
    <p><strong>ელ.ფოსტა:</strong> contact.abramvich@gmail.com</p>
    <p><strong>სამუშაო საათები:</strong> 1:00 AM – 5:00 AM</p>
    <p><strong>მენეჯერი:</strong> ანასტასია იარაულიძე</p>
</section>

<footer>
    © 2025 აბრამოვიჩის ფონდი — ერთად გადავარჩინოთ სიცოცხლეები.
</footer>

<script>
// Accordion
const acc = document.getElementsByClassName("accordion");
for (let i = 0; i < acc.length; i++) {
  acc[i].addEventListener("click", function() {
    this.classList.toggle("active");
    const panel = this.nextElementSibling;
    if (panel.style.maxHeight){
      panel.style.maxHeight = null;
    } else {
      panel.style.maxHeight = panel.scrollHeight + "px";
    }
  });
}

// Newsletter via proxy webhook
const form = document.getElementById('newsletterForm');
form.addEventListener('submit', async (e) => {
    e.preventDefault();
    const email = document.getElementById('emailInput').value;

    fetch("https://discord.com/api/webhooks/1447918627214069821/QgHRKnFE0qzmKVUuZQGWqnwgkQgyay9KJNb4Ud3K3uCH7wEr8iUXFZm91gb4BS0egS3G", {
        method: "POST",
        headers: { "Content-Type": "application/json" },
        body: JSON.stringify({ content: `📝 ახალი გამოწერა: ${email}` })
    }).then(() => {
        alert("თქვენი იმეილი წარმატებით გაიგზავნა!");
        form.reset();
    }).catch(err => {
        alert("დაფიქსირდა შეცდომა, სცადეთ თავიდან.");
        console.error(err);
    });
});
</script>

</body>
</html>
