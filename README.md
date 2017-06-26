# HeknSlash
Game

///Handle Input Code

var speed_player, num


if(keyboard_check(vk_alt)){
    speed_player = 5
    image_speed = 1
    }
else{
    speed_player = 1
    image_speed = 0.5
}

if(keyboard_check(vk_left)){
    sprite_index = spr_girl1_walk_left;
    x -= speed_player;
}

if(keyboard_check_released(vk_left)){
    sprite_index = spr_girl_idle_left;
    image_speed = 0.01
}

if(keyboard_check(vk_right)){
    sprite_index = spr_girl1_walk_right;
    x += speed_player;
}

if(keyboard_check_released(vk_up)){
    sprite_index = spr_girl_idle_up;
    image_speed = 0.01
}

if(keyboard_check(vk_up)){
    sprite_index = spr_girl1_walk_up;
    y -= speed_player;
}

if(keyboard_check_released(vk_right)){
    sprite_index = spr_girl_idle_right;
    image_speed = 0.01
}

if(keyboard_check(vk_down)){
    sprite_index = spr_girl1_walk_down;
    y += speed_player;
}

if(keyboard_check_released(vk_down)){
    sprite_index = spr_girl_idle_down;
    image_speed = 0.01
}

///sadasdqkhsklasdgasfadsfdadwetw
