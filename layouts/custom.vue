<template>
  <div>
    <Navbar expand="lg" theme="light" background-color="light">
      <Container type="fluid">
        <NavbarBrand>Ferienwohnung</NavbarBrand>
        <NavbarToggler />
        <NavbarCollapse>
          <NavbarNav>
            <NavLink to="/" active>Startseite</NavLink>
            <NavLink to="/gallery">Gallerie</NavLink>
            <NavLink>Kontakt</NavLink>
          </NavbarNav>
        </NavbarCollapse>
      </Container>
    </Navbar>

    <slot />
  </div>
</template>
