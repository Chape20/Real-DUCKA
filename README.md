///obj_player Create Event
grav = 0.2;
hsp = 0;
vsp = 0;
jumpspeed = 7;
movespeed = 4;

///obj_player Step Event
key_right = keyboard_check(vk_right);
key_left = keyboard_check(vk_left);
key_jump = keyboard_check_pressed(vk_space);

//Reacting to Inputs
move = key_left + key_right;
hsp = move * movespeed;
if(vsp<10) vsp +=grav;

if(place_meeting(x,y+1,obj_wall);
{
  vsp = key_jump * -jumpspeed
}

//Horizontal Collision
