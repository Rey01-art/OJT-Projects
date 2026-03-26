<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Profile Tree</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>

<div class="container">

  <div class="banner">
     <img src="images/tesda-banner.png" alt="TESDA Banner">
  </div>

  <div class="profile">
    <img src="images/user.png" alt="Profile">
    <div class="name">Juan Dela Cruz</div>
    <div class="info">Designation: Trainer</div>
    <div class="info">Agency: TESDA - SICAT</div>
  </div>

  <div class="links">
    <a href="tel:+639123456789" onclick="handleContact(event)">📱 Contact Number</a>

    <!-- EMAIL BUTTON -->
    <a href="#" onclick="openEmail(event)">📧 Email</a>

    <a href="https://facebook.com/" target="_blank">🌐 Facebook Profile</a>
  </div>

</div>

<script>
// CONTACT (CALL / COPY)
function handleContact(event) {
  event.preventDefault();
  const number = "+639123456789";
  const choice = confirm("Press OK to Call 📞\nPress Cancel to Copy 📋");
  if (choice) {
    window.location.href = "tel:" + number;
  } else {
    copyToClipboard(number);
  }
}

// COPY FUNCTION
function copyToClipboard(text) {
  if (navigator.clipboard && window.isSecureContext) {
    navigator.clipboard.writeText(text)
      .then(() => showToast("Number copied: " + text))
      .catch(() => fallbackCopy(text));
  } else {
    fallbackCopy(text);
  }
}

function fallbackCopy(text) {
  const textarea = document.createElement("textarea");
  textarea.value = text;
  textarea.style.position = "fixed";
  textarea.style.opacity = "0";
  document.body.appendChild(textarea);
  textarea.focus();
  textarea.select();
  try {
    document.execCommand("copy");
    showToast("Number copied: " + text);
  } catch (err) {
    alert("Failed to copy. Please copy manually: " + text);
  }
  document.body.removeChild(textarea);
}

// TOAST
function showToast(message) {
  const toast = document.createElement("div");
  toast.className = "toast";
  toast.innerText = message;
  document.body.appendChild(toast);
  setTimeout(() => toast.classList.add("show"), 50);
  setTimeout(() => {
    toast.classList.remove("show");
    setTimeout(() => toast.remove(), 300);
  }, 2000);
}

// EMAIL BUTTON: CROSS-PLATFORM
function openEmail(event) {
  event.preventDefault();
  
  const email = "juandelacruz@gmail.com";
  const subject = "Inquiry";
  const body = "Hello Juan,";

  // Gmail web compose for desktop
  const gmailWeb = `https://mail.google.com/mail/?view=cm&fs=1&to=${encodeURIComponent(email)}&su=${encodeURIComponent(subject)}&body=${encodeURIComponent(body)}`;
  // Gmail intent for Android
  const gmailIntent = `intent://compose?to=${email}&subject=${encodeURIComponent(subject)}&body=${encodeURIComponent(body)}#Intent;scheme=mailto;package=com.google.android.gm;end;`;
  // Fallback mailto
  const mailtoFallback = `mailto:${email}?subject=${encodeURIComponent(subject)}&body=${encodeURIComponent(body)}`;

  const ua = navigator.userAgent || navigator.vendor || window.opera;

  if (/android/i.test(ua)) {
    window.location.href = gmailIntent;
    setTimeout(() => window.location.href = mailtoFallback, 800);
  } else if (/iPad|iPhone|iPod/.test(ua) && !window.MSStream) {
    window.location.href = mailtoFallback;
  } else {
    window.open(gmailWeb, "_blank");
  }
}
</script>

</body>
</html>