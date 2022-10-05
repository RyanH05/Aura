import pygame

#import RPi.GPIO as GPIO
import time

#definitions


#Initialize Pygame
pygame.init()

#set the width and height of the screen [width, height]
size = (600,800)
screen = pygame.display.set_mode(size)
pygame.display.set_caption("My Game")

#Set main loop complete
complete = false

#set the speed of loops
clock = pygame.time.Clock()

#---------Main Program Loop--------
while not complete:
  #--Main event loop
  for event in pygame.event.get():
    if event.type == pygame.QUIT
    `complete = True

  #-Add game logic should go here
  
  #-Screen clearing code goes here
  screen.fill((0,0,0))
  
  #-Draw objects on the screen
  
  #-Update the screen with our drawing
  pygame.display.flip()
  
  #set frame rate
  clock.tick(30)
  
#close the window and quit.
pygame.quit()
   
