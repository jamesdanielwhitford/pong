# A game is an infinite loop
Check inputs, update game state based on inputs, render those updates on screen

# 2D co-ordinate system for drawing on screen
Co-ordinates start top left at (0,0)

# Function in love
## love.load
Start-up functon, whatever we want to run at the beginning of our applciaton

## love.update(dt)
Executed every frame, in delta time, change app based on how much time is passed

## love.draw
Rendering behaviour

## love.graphics.printf(text, x, y, width, align)
Draws to screen

## love.window.setMode()
Sets up window

## love.graphics.setDefaultFilter
Font or images get a filter by default, whenever we magnify or downscale a picture, a blur will stop pixelation. If pixels is what you want, that's not good.

## love.keypressed(key)
Callback function that executes when key pressed

## love.event.quit()
terminates application.
