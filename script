(function () {
  var nav = document.getElementById('nav');
  if (!nav) return;

  function updateNav() {
    if (window.scrollY > 40) {
      nav.classList.add('solid');
    } else {
      nav.classList.remove('solid');
    }
  }

  updateNav();
  window.addEventListener('scroll', updateNav, { passive: true });
})();
