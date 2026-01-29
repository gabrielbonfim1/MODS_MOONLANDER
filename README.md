# MODS_MOONLANDER

No arquivo keymap.c colar no fim da função rgb_matrix_indicators_user(void){
  ...

  if (host_keyboard_led_state().caps_lock){
    rgb_matrix_set_color(0,255,0,0);
    rgb_matrix_set_color(5,255,0,0);
    rgb_matrix_set_color(10,255,0,0);
    rgb_matrix_set_color(15,255,0,0);
    rgb_matrix_set_color(20,255,0,0);
    rgb_matrix_set_color(25,255,0,0);
    rgb_matrix_set_color(36,255,0,0);
    rgb_matrix_set_color(41,255,0,0);
    rgb_matrix_set_color(46,255,0,0);
    rgb_matrix_set_color(51,255,0,0);
    rgb_matrix_set_color(56,255,0,0);
    rgb_matrix_set_color(61,255,0,0);
  }

}
