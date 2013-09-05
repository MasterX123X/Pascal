Pascal
======

javascript:(function() {
  addCookies(1000000);
  spawnGoldenCookie(50);
  setCPS(500);
  Game.cookiesPs = 100000;
  //upCPS(10);
  upgradeAll();
  archivmentUnlockAll();
  buyAllBuildings(100);
  /* Functions */
  function addCookies(num) {
    Game.cookies += num;
  }
