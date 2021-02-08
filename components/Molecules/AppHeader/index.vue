<template>
  <header class="app-header">
    <div class="app-header__logo">
      <AppLogo />
    </div>
    UI-Kit
  </header>
</template>

<style lang="scss" scoped>
.app-header {
  display: flex;
  align-items: center;
  height: 8vh;
  padding: 16px;
  box-shadow: 0 0 4px 4px rgba(0, 0, 0, 0.05);
  font-size: 32px;
  font-weight: bold;
  &__logo {
    width: 40px;
    height: 40px;
    margin-right: 8px;
  }
}
</style>
