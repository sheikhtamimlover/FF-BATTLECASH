<div align="center">

<style>
@keyframes float {
  0%, 100% { transform: translateY(0px); }
  50% { transform: translateY(-20px); }
}

@keyframes glow {
  0%, 100% { text-shadow: 0 0 10px rgba(255, 215, 0, 0.5), 0 0 20px rgba(255, 140, 0, 0.3); }
  50% { text-shadow: 0 0 20px rgba(255, 215, 0, 0.8), 0 0 30px rgba(255, 140, 0, 0.6); }
}

@keyframes slideInDown {
  from {
    opacity: 0;
    transform: translateY(-30px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

.icon-circle {
  width: 180px;
  height: 180px;
  border-radius: 50%;
  overflow: hidden;
  margin: 0 auto 20px;
  box-shadow: 0 0 40px rgba(255, 140, 0, 0.6), 0 20px 60px rgba(0, 0, 0, 0.3);
  animation: float 3s ease-in-out infinite;
  border: 5px solid #FFD700;
}

.icon-circle img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}

.title-3d {
  font-size: 48px;
  font-weight: 900;
  background: linear-gradient(135deg, #FFD700, #FFA500, #FF6347);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
  text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.1);
  animation: glow 2s ease-in-out infinite, slideInDown 0.8s ease-out;
  letter-spacing: 2px;
  text-transform: uppercase;
}

.subtitle-3d {
  font-size: 18px;
  font-weight: 600;
  color: #333;
  text-shadow: 2px 2px 8px rgba(255, 140, 0, 0.3);
  margin-top: 10px;
  animation: slideInDown 1s ease-out 0.2s both;
}
</style>

<div class="icon-circle">
  <img src="assest/fficon.jpg" alt="FF BATTLECASH Icon">
</div>

<h1 class="title-3d">FF BATTLECASH</h1>
<p class="subtitle-3d">🏆 The Ultimate Free Fire Tournament Earning App for Bangladesh 🏆</p>

</div>

## 📱 About FF BATTLECASH

FF BATTLECASH is an Android application designed specifically for **Free Fire enthusiasts in Bangladesh (BD Zone)**. This innovative platform allows players to:

- 🎮 **Join Tournaments**: Participate in exciting Free Fire matches with real prize pools
- 💰 **Earn Real Money**: Win tournaments and earn actual money
- ⚡ **Quick Matches**: Play multiple matches and accumulate earnings
- 🏆 **Competitive Ranking**: Climb the leaderboard and compete with top players
- 💳 **Easy Withdrawal**: Quick and secure payment methods

Perfect for **Bangladeshi gamers** who want to monetize their Free Fire skills and compete in real tournaments.

---

## 🎯 App Features

<style>
.features-container {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 20px;
  max-width: 1200px;
  margin: 40px auto;
  padding: 20px;
}

@media (max-width: 1024px) {
  .features-container {
    grid-template-columns: repeat(2, 1fr);
  }
}

@media (max-width: 768px) {
  .features-container {
    grid-template-columns: 1fr;
  }
}

.feature-card {
  background: linear-gradient(135deg, rgba(255, 215, 0, 0.1), rgba(255, 140, 0, 0.05));
  border: 2px solid rgba(255, 140, 0, 0.3);
  border-radius: 15px;
  padding: 25px;
  text-align: center;
  transition: all 0.3s ease;
  box-shadow: 0 5px 15px rgba(255, 140, 0, 0.15);
  transform: perspective(1000px) rotateX(0deg);
}

.feature-card:hover {
  transform: perspective(1000px) rotateX(5deg) translateY(-10px);
  box-shadow: 0 15px 40px rgba(255, 140, 0, 0.3);
  border-color: rgba(255, 140, 0, 0.6);
  background: linear-gradient(135deg, rgba(255, 215, 0, 0.15), rgba(255, 140, 0, 0.1));
}

.feature-icon {
  font-size: 48px;
  margin-bottom: 15px;
  animation: float 3s ease-in-out infinite;
}

.feature-card h3 {
  color: #FF6347;
  font-size: 18px;
  margin: 15px 0;
  text-transform: uppercase;
  letter-spacing: 1px;
}

.feature-card p {
  color: #555;
  font-size: 14px;
  line-height: 1.6;
}
</style>

<div class="features-container">
  <div class="feature-card">
    <div class="feature-icon">🎮</div>
    <h3>Join Tournaments</h3>
    <p>Participate in exciting Free Fire matches with real prize pools. Compete with players of similar skill levels.</p>
  </div>
  
  <div class="feature-card">
    <div class="feature-icon">💰</div>
    <h3>Earn Real Money</h3>
    <p>Win tournaments and earn actual money. Get paid directly to your preferred payment method instantly.</p>
  </div>
  
  <div class="feature-card">
    <div class="feature-icon">⚡</div>
    <h3>Quick Matches</h3>
    <p>Play multiple matches quickly and accumulate earnings faster. No long waiting times between tournaments.</p>
  </div>
  
  <div class="feature-card">
    <div class="feature-icon">🏆</div>
    <h3>Competitive Ranking</h3>
    <p>Climb the leaderboard and compete with top players. Track your progress and achievements in real-time.</p>
  </div>
  
  <div class="feature-card">
    <div class="feature-icon">💳</div>
    <h3>Secure Payments</h3>
    <p>Add money and withdraw earnings safely. Multiple payment options with transparent pricing, no hidden charges.</p>
  </div>
  
  <div class="feature-card">
    <div class="feature-icon">🔐</div>
    <h3>Safe & Secure</h3>
    <p>Your data and transactions are fully protected. Industry-standard security measures for your peace of mind.</p>
  </div>
</div>

---

## 📸 App Screenshots Gallery

<div align="center">

<style>
.screenshot-grid {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 15px;
  max-width: 1000px;
  margin: 30px auto;
  padding: 20px;
}

@media (max-width: 1024px) {
  .screenshot-grid {
    grid-template-columns: repeat(3, 1fr);
  }
}

@media (max-width: 768px) {
  .screenshot-grid {
    grid-template-columns: repeat(2, 1fr);
  }
}

@media (max-width: 480px) {
  .screenshot-grid {
    grid-template-columns: 1fr;
  }
}

.screenshot-item {
  position: relative;
  overflow: hidden;
  border-radius: 15px;
  box-shadow: 0 5px 20px rgba(255, 140, 0, 0.2);
  transition: all 0.3s ease;
  background: #f0f0f0;
}

.screenshot-item:hover {
  transform: translateY(-10px) scale(1.05);
  box-shadow: 0 15px 40px rgba(255, 140, 0, 0.4);
}

.screenshot-item img {
  width: 100%;
  height: 280px;
  object-fit: cover;
  display: block;
}

.screenshot-label {
  position: absolute;
  bottom: 0;
  left: 0;
  right: 0;
  background: linear-gradient(to top, rgba(0,0,0,0.8), transparent);
  color: white;
  padding: 15px 10px 10px;
  font-size: 12px;
  font-weight: 600;
  text-align: center;
}

.profile-circle {
  width: 120px;
  height: 120px;
  border-radius: 50%;
  overflow: hidden;
  margin: 20px auto;
  box-shadow: 0 0 30px rgba(255, 140, 0, 0.4);
  border: 4px solid #FFD700;
}

.profile-circle img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}
</style>

<div class="profile-circle">
  <img src="assest/profile.jpg" alt="User Profile">
</div>

<h3 style="color: #FF6347; text-transform: uppercase; letter-spacing: 1px; margin-bottom: 25px;">📱 App Interface Showcase</h3>

<div class="screenshot-grid">
  <div class="screenshot-item">
    <img src="assest/loginpage.jpg" alt="Login Page">
    <div class="screenshot-label">🔐 Login Page</div>
  </div>
  
  <div class="screenshot-item">
    <img src="assest/createpage.jpg" alt="Create Account">
    <div class="screenshot-label">📝 Create Account</div>
  </div>
  
  <div class="screenshot-item">
    <img src="assest/forgetpage.jpg" alt="Forget Password">
    <div class="screenshot-label">🔑 Forget Password</div>
  </div>
  
  <div class="screenshot-item">
    <img src="assest/home.jpg" alt="Home Screen">
    <div class="screenshot-label">🏠 Home Screen</div>
  </div>
  
  <div class="screenshot-item">
    <img src="assest/matchbar.jpg" alt="Match Bar">
    <div class="screenshot-label">⚔️ Match Bar</div>
  </div>
  
  <div class="screenshot-item">
    <img src="assest/rank.jpg" alt="Rankings">
    <div class="screenshot-label">🏆 Rankings</div>
  </div>
  
  <div class="screenshot-item">
    <img src="assest/gift.jpg" alt="Gift System">
    <div class="screenshot-label">🎁 Gift System</div>
  </div>
  
  <div class="screenshot-item">
    <img src="assest/aitools.jpg" alt="AI Tools">
    <div class="screenshot-label">🤖 AI Tools</div>
  </div>
  
  <div class="screenshot-item">
    <img src="assest/addmoney.jpg" alt="Add Money">
    <div class="screenshot-label">💳 Add Money</div>
  </div>
  
  <div class="screenshot-item">
    <img src="assest/withdraw.jpg" alt="Withdraw">
    <div class="screenshot-label">💰 Withdraw</div>
  </div>
  
  <div class="screenshot-item">
    <img src="assest/supportchat.jpg" alt="Support Chat">
    <div class="screenshot-label">💬 Support Chat</div>
  </div>
</div>

</div>

---

## 🎥 Video Tutorial

<style>
.video-section {
  background: linear-gradient(135deg, rgba(255, 140, 0, 0.1), rgba(255, 215, 0, 0.05));
  border-radius: 20px;
  padding: 40px 20px;
  margin: 40px auto;
  max-width: 800px;
  text-align: center;
  box-shadow: 0 10px 40px rgba(255, 140, 0, 0.2);
}

.video-title {
  font-size: 28px;
  font-weight: 700;
  color: #FF6347;
  margin-bottom: 25px;
  text-transform: uppercase;
  letter-spacing: 2px;
  text-shadow: 2px 2px 4px rgba(255, 140, 0, 0.2);
}

.youtube-link-btn {
  display: inline-block;
  background: linear-gradient(135deg, #FFD700, #FFA500);
  color: white;
  padding: 15px 40px;
  border-radius: 50px;
  text-decoration: none;
  font-weight: 700;
  font-size: 16px;
  transition: all 0.3s ease;
  box-shadow: 0 5px 20px rgba(255, 140, 0, 0.4);
  text-transform: uppercase;
  letter-spacing: 1px;
}

.youtube-link-btn:hover {
  transform: translateY(-5px) scale(1.05);
  box-shadow: 0 10px 30px rgba(255, 140, 0, 0.6);
}
</style>

<div class="video-section">
  <h3 class="video-title">📺 Learn How to Use FF BATTLECASH</h3>
  <p style="color: #666; margin-bottom: 20px; font-size: 16px;">Watch our comprehensive tutorial to get started</p>
  
  <a href="https://www.youtube.com/watch?v=GO1qdK3TzwA&t=344s" class="youtube-link-btn">▶ Watch Tutorial on YouTube</a>
</div>

---

## 🤝 Join Our Community

<style>
.community-section {
  background: linear-gradient(135deg, rgba(255, 215, 0, 0.08), rgba(255, 140, 0, 0.08));
  border-radius: 20px;
  padding: 40px 20px;
  margin: 40px auto;
  max-width: 1000px;
}

.community-title {
  text-align: center;
  font-size: 28px;
  font-weight: 700;
  color: #FF6347;
  margin-bottom: 40px;
  text-transform: uppercase;
  letter-spacing: 2px;
}

.social-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 20px;
  margin-bottom: 20px;
}

@media (max-width: 768px) {
  .social-grid {
    grid-template-columns: repeat(2, 1fr);
  }
}

@media (max-width: 480px) {
  .social-grid {
    grid-template-columns: 1fr;
  }
}

.social-card {
  background: white;
  border: 2px solid rgba(255, 140, 0, 0.3);
  border-radius: 15px;
  padding: 20px;
  text-align: center;
  transition: all 0.3s ease;
  box-shadow: 0 5px 15px rgba(255, 140, 0, 0.1);
}

.social-card:hover {
  transform: translateY(-8px) scale(1.02);
  box-shadow: 0 15px 40px rgba(255, 140, 0, 0.25);
  border-color: rgba(255, 140, 0, 0.6);
}

.social-icon {
  font-size: 40px;
  margin-bottom: 10px;
}

.social-card h4 {
  color: #FF6347;
  margin: 10px 0;
  font-size: 16px;
  text-transform: uppercase;
  letter-spacing: 1px;
}

.social-link {
  display: inline-block;
  background: linear-gradient(135deg, #FFD700, #FFA500);
  color: white;
  padding: 10px 20px;
  border-radius: 25px;
  text-decoration: none;
  font-size: 13px;
  font-weight: 600;
  transition: all 0.3s ease;
}

.social-link:hover {
  transform: scale(1.05);
  box-shadow: 0 5px 15px rgba(255, 140, 0, 0.4);
}
</style>

<div class="community-section">
  <h3 class="community-title">Connect & Stay Updated</h3>
  
  <div class="social-grid">
    <div class="social-card">
      <div class="social-icon">📺</div>
      <h4>YouTube</h4>
      <p style="color: #666; font-size: 13px; margin-bottom: 10px;">Subscribe for updates</p>
      <a href="https://youtube.com/@ffbattlecash" class="social-link">Subscribe</a>
    </div>
    
    <div class="social-card">
      <div class="social-icon">🎵</div>
      <h4>TikTok</h4>
      <p style="color: #666; font-size: 13px; margin-bottom: 10px;">Follow for tips & tricks</p>
      <a href="https://www.tiktok.com/@ff.battlecash" class="social-link">Follow</a>
    </div>
    
    <div class="social-card">
      <div class="social-icon">💬</div>
      <h4>WhatsApp</h4>
      <p style="color: #666; font-size: 13px; margin-bottom: 10px;">Join our community</p>
      <a href="https://chat.whatsapp.com/DbmZs0n6Z931P5vaj8PYGK?s=cl&p=i&ilr=4&amv=2" class="social-link">Join</a>
    </div>
    
    <div class="social-card">
      <div class="social-icon">📘</div>
      <h4>Facebook</h4>
      <p style="color: #666; font-size: 13px; margin-bottom: 10px;">Like our page</p>
      <a href="https://www.facebook.com/share/18zga4jJnY/?mibextid=wwXIfr" class="social-link">Like</a>
    </div>
    
    <div class="social-card">
      <div class="social-icon">📸</div>
      <h4>Instagram</h4>
      <p style="color: #666; font-size: 13px; margin-bottom: 10px;">Follow for exclusive content</p>
      <a href="https://instagram.com/sheikh.tamim_lover" class="social-link">Follow</a>
    </div>
    
    <div class="social-card">
      <div class="social-icon">📧</div>
      <h4>Email</h4>
      <p style="color: #666; font-size: 13px; margin-bottom: 10px;">Get in touch</p>
      <a href="mailto:tamimsheikh142@gmail.com" class="social-link">Contact</a>
    </div>
  </div>
</div>

---

## 📧 Support & Contact

<style>
.contact-section {
  background: linear-gradient(135deg, rgba(255, 140, 0, 0.15), rgba(255, 215, 0, 0.08));
  border-left: 5px solid #FF6347;
  border-radius: 10px;
  padding: 30px;
  margin: 40px auto;
  max-width: 600px;
  text-align: center;
  box-shadow: 0 5px 20px rgba(255, 140, 0, 0.15);
}

.contact-item {
  margin: 15px 0;
  font-size: 16px;
  color: #333;
}

.contact-item strong {
  color: #FF6347;
  font-weight: 700;
}

.contact-link {
  color: #FFA500;
  text-decoration: none;
  font-weight: 600;
  transition: all 0.3s ease;
}

.contact-link:hover {
  color: #FF6347;
  text-decoration: underline;
}
</style>

<div class="contact-section">
  <h3 style="color: #FF6347; margin-bottom: 20px; text-transform: uppercase; letter-spacing: 1px;">Need Help? Get In Touch!</h3>
  
  <div class="contact-item">
    <strong>📧 Email:</strong> 
    <a href="mailto:tamimsheikh142@gmail.com" class="contact-link">tamimsheikh142@gmail.com</a>
  </div>
  
  <div class="contact-item">
    <strong>📸 Instagram:</strong> 
    <a href="https://instagram.com/sheikh.tamim_lover" class="contact-link">@sheikh.tamim_lover</a>
  </div>
  
  <div class="contact-item">
    <strong>💬 WhatsApp:</strong> 
    <a href="https://chat.whatsapp.com/DbmZs0n6Z931P5vaj8PYGK?s=cl&p=i&ilr=4&amv=2" class="contact-link">Join Our Group</a>
  </div>
  
  <p style="color: #999; font-size: 14px; margin-top: 15px;">We're here to help! Reach out anytime for support or inquiries.</p>
</div>

---

---

## 📄 License & Author

<style>
.author-section {
  background: linear-gradient(135deg, #FFD700, #FFA500);
  border-radius: 15px;
  padding: 40px;
  margin: 40px auto;
  max-width: 700px;
  text-align: center;
  box-shadow: 0 10px 40px rgba(255, 140, 0, 0.3);
  color: white;
}

.author-name {
  font-size: 32px;
  font-weight: 900;
  text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.2);
  margin: 20px 0;
  text-transform: uppercase;
  letter-spacing: 2px;
}

.author-info {
  background: rgba(0, 0, 0, 0.1);
  border-radius: 10px;
  padding: 20px;
  margin: 20px 0;
  backdrop-filter: blur(10px);
}

.author-info p {
  margin: 10px 0;
  font-size: 16px;
  font-weight: 600;
}

.author-info a {
  color: white;
  text-decoration: none;
  font-weight: 700;
  transition: all 0.3s ease;
  border-bottom: 2px solid white;
}

.author-info a:hover {
  text-decoration: underline;
}
</style>

<div class="author-section">
  <h3 style="text-transform: uppercase; letter-spacing: 2px; text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.2); margin-bottom: 10px;">👨‍💻 Created & Developed By</h3>
  
  <div class="author-name">Sheikh Tamim</div>
  
  <div class="author-info">
    <p>
      <strong>📧 Email:</strong><br>
      <a href="mailto:tamimsheikh142@gmail.com">tamimsheikh142@gmail.com</a>
    </p>
    
    <p>
      <strong>📸 Instagram:</strong><br>
      <a href="https://instagram.com/sheikh.tamim_lover">@sheikh.tamim_lover</a>
    </p>
    
    <p style="font-size: 14px; margin-top: 15px; opacity: 0.95;">
      Designed & developed for the Free Fire gaming community in Bangladesh (BD Zone)
    </p>
  </div>
  
  <p style="font-size: 12px; margin-top: 20px; opacity: 0.9;">© 2026 FF BATTLECASH | All Rights Reserved</p>
</div>

---

## ⚠️ Disclaimer

<style>
.disclaimer-section {
  background: linear-gradient(135deg, rgba(255, 105, 180, 0.1), rgba(255, 69, 0, 0.1));
  border: 2px dashed #FF6347;
  border-radius: 10px;
  padding: 25px;
  margin: 40px auto;
  max-width: 800px;
  font-size: 14px;
  color: #555;
  text-align: center;
}

.footer-section {
  background: linear-gradient(135deg, #222, #333);
  color: white;
  padding: 40px 20px;
  margin-top: 40px;
  border-radius: 15px 15px 0 0;
  text-align: center;
}

.download-cta {
  background: linear-gradient(135deg, #FFD700, #FFA500);
  color: white;
  padding: 20px;
  border-radius: 15px;
  margin: 30px auto;
  max-width: 600px;
  font-size: 20px;
  font-weight: 900;
  text-transform: uppercase;
  letter-spacing: 2px;
  box-shadow: 0 10px 40px rgba(255, 140, 0, 0.4);
  animation: glow 2s ease-in-out infinite;
  text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3);
}
</style>

<div class="disclaimer-section">
  <strong>⚖️ Important Notice:</strong><br><br>
  FF BATTLECASH is an independent platform for organizing tournaments and is not affiliated with or endorsed by Garena or Free Fire. All trademarks, logos, and brand names belong to their respective owners.
</div>

---

<div class="download-cta">
  🚀 Start Earning from Your Free Fire Skills Today! 🚀
</div>

<div class="footer-section">
  <h3 style="margin-bottom: 20px; text-transform: uppercase; letter-spacing: 2px;">🎮 FF BATTLECASH 🎮</h3>
  
  <p style="margin: 15px 0; font-size: 16px; line-height: 1.8;">
    The ultimate platform for Free Fire players in Bangladesh to compete, showcase their skills, and earn real money!
  </p>
  
  <p style="margin-top: 30px; font-size: 13px; color: #aaa; border-top: 1px solid #555; padding-top: 20px;">
    © 2026 FF BATTLECASH | Developed by Sheikh Tamim<br>
    <a href="https://instagram.com/sheikh.tamim_lover" style="color: #FFD700; text-decoration: none; font-weight: 600;">@sheikh.tamim_lover</a> 
    | 
    <a href="mailto:tamimsheikh142@gmail.com" style="color: #FFD700; text-decoration: none; font-weight: 600;">Contact</a>
  </p>
</div> 
