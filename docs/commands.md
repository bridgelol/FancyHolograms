# FancyHolograms Commands

This section provides detailed information about the various commands available in FancyHolograms, allowing you to make
the
most out of its features.

## /FancyHolograms ...

### version

Description: Shows the current version of the plugin<br>
Syntax: ``/FancyHolograms version``<br>
Permission: ``FancyHolograms.admin``

### save

Description: Saves all holograms<br>
Syntax: ``/FancyHolograms save``<br>
Permission: ``FancyHolograms.admin``

### reload

Description: Reloads the config and holograms<br>
Syntax: ``/FancyHolograms reload``<br>
Permission: ``FancyHolograms.admin``

## /Holograms ...

### help

Description: Shows a list of all subcommands<br>
Syntax: ``/Hologram help``<br>
Permission: ``FancyHolograms.admin``

### list

Description: Shows a list of all holograms<br>
Syntax: ``/Hologram list``<br>
Permission: ``FancyHolograms.admin``

### create

Description: Creates a new hologram at your location<br>
Syntax: ``/Hologram create (name)``<br>
Permission: ``FancyHolograms.admin``

### remove

Description: Removes a certain hologram<br>
Syntax: ``/Hologram remove (hologram)``<br>
Permission: ``FancyHolograms.admin``

### copy

Description: Creates a copy of a hologram<br>
Syntax: ``/Hologram copy (hologram) (new name)``<br>
Permission: ``FancyHolograms.admin``

### info

Description: Shows you all information about the hologram<br>
Syntax: ``/Hologram info (hologram)``<br>
Permission: ``FancyHolograms.admin``

## General hologram modification

These commands can be run for any hologram type (text, item and block).

### moveHere

Description: Teleports the hologram to you<br>
Syntax: ``/Hologram edit (hologram) moveHere``<br>
Alias: ``/Hologram edit (hologram) position``<br>
Permission: ``FancyHolograms.admin``

### moveTo

Description: Teleports the hologram to the location<br>
Syntax: ``/Hologram edit (hologram) moveTo (x) (y) (z) [yaw] [pitch]``<br>
Permission: ``FancyHolograms.admin``

### rotate

Description: Rotates the hologram around the y-axis<br>
Syntax: ``/Hologram edit (hologram) rotate (degrees)``<br>
Permission: ``FancyHolograms.admin``

### rotatepitch

Description: Rotates the hologram around the x-axis<br>
Syntax: ``/Hologram edit (hologram) rotatepitch (degrees)``<br>
Permission: ``FancyHolograms.admin``

### visibilityDistance

Description: Sets from how far away players can see the hologram (-1 for default distance)<br>
Syntax: ``/Hologram edit (hologram) visibilityDistance (distance)``<br>
Permission: ``FancyHolograms.admin``

### scale

Description: Sets the scale (can be floats)<br>
Syntax: ``/Hologram edit (hologram) scale (factor)``<br>
Permission: ``FancyHolograms.admin``

### billboard

Description: Sets the billboard<br>
Syntax: ``/Hologram edit (hologram) billboard (center | fixed | vertical | horizontal)``<br>
Permission: ``FancyHolograms.admin``

### shadowStrength

Description: Sets the shadow strength<br>
Syntax: ``/Hologram edit (hologram) shadowStrength (strength)``<br>
Permission: ``FancyHolograms.admin``

### shadowRadius

Description: Sets the shadow radius<br>
Syntax: ``/Hologram edit (hologram) shadowRadius (radius)``<br>
Permission: ``FancyHolograms.admin``

### linkWithNpc

Description: Links a hologram with an NPC (requires FancyNpcs)<br>
Syntax: ``/Hologram edit (hologram) linkWithNpc (npc)``<br>
Permission: ``FancyHolograms.admin``

### unlinkWithNpc

Description: Unlinks the hologram from the NPC<br>
Syntax: ``/Hologram edit (hologram) unlinkWithNpc``<br>
Permission: ``FancyHolograms.admin``

## Text hologram modification

These commands can be run for all **text** holograms.

### setLine

Description: Sets the content of the line<br>
Syntax: ``/Hologram edit (hologram) setLine (line) (text...)``<br>
Permission: ``FancyHolograms.admin``

### addLine

Description: Adds a line at the bottom<br>
Syntax: ``/Hologram edit (hologram) addLine (text...)``<br>
Permission: ``FancyHolograms.admin``

### removeLine

Description: Removes a line<br>
Syntax: ``/Hologram edit (hologram) removeLine (line)``<br>
Permission: ``FancyHolograms.admin``

### insertBefore

Description: Adds a line after another<br>
Syntax: ``/Hologram edit (hologram) insertBefore (line) (text...)``<br>
Permission: ``FancyHolograms.admin``

### insertAfter

Description: Adds a line before another<br>
Syntax: ``/Hologram edit (hologram) insertAfter (line) (text...)``<br>
Permission: ``FancyHolograms.admin``

### updateTextInterval

Description: Sets the interval for refreshing the text (useful for
placeholders)<br>
Syntax: ``/Hologram edit (hologram) updateTextInterval (ticks | seconds | minutes)``<br>
Example ticks:``/Hologram edit (hologram) updateTextInterval (15)``<br>
Example seconds:``/Hologram edit (hologram) updateTextInterval (5s)``<br>
Example minutes:``/Hologram edit (hologram) updateTextInterval (5min)``<br>
Permission: ``FancyHolograms.admin``

### background

Description: Sets the background color<br>
Syntax: ``/Hologram edit (hologram) background (color)``<br>
Permission: ``FancyHolograms.admin``

### textShadow

Description: Enables/disables the text shadow<br>
Syntax: ``/Hologram edit (hologram) textShadow (true|false)``<br>
Permission: ``FancyHolograms.admin``

### textAlignment

Description: Enables/disables the text shadow<br>
Syntax: ``/Hologram edit (hologram) textAlignment (center | left | right)``<br>
Permission: ``FancyHolograms.admin``

## Item hologram modification

These commands can be run for all **item** holograms.

### item

Description: Sets the hologram item you are holding in your main hand<br>
Syntax: ``/Hologram edit (hologram) item``<br>
Permission: ``FancyHolograms.admin``

## Block hologram modification

These commands can be run for all **block** holograms.

### block

Description: Sets the hologram block<br>
Syntax: ``/Hologram edit (hologram) block (block type)``<br>
Permission: ``FancyHolograms.admin``