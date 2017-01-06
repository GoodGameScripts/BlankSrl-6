# BlankSrl-6
The srl-6 without all the RS3 functions,  So makes for a perfect base for any RSPS<br>
To use this include, download and extract it to your simba/includes directory and rename it to  BlankSrl-6 or the rsps's name your using and adjust the line below to the new name.<br>
Then add this to the top  of your script. {$i BlankSrl-6/srl.simba} <br>
All though,if you want to add more functionality, you will have to create new simba files,procedures, and functions. <br>
To add a file to your include, follow the steps below. <br>
srl.simba<br>
{$DEFINE $DEFINE SRL6}<br>

{$include_once utilities/wrappers.simba}<br>
{$include_once utilities/time.simba}<br>
{$include_once core/debug.simba}<br>
{$include_once core/globals.simba}<br>
{$include_once utilities/math.simba}<br>
{$include_once core/mouse.simba}<br>
{$include_once utilities/drawing.simba}<br>
{$include_once utilities/pixelshift.simba}<br>
{$include_once utilities/types/types.simba}<br>
{$include_once utilities/color.simba}<br>

<strong>{$include_once location/example.simba} -add this line  and adjust to the files location and name, repeat as needed </strong> <br>

procedure SetupRSPSinclude; -- call this in the main loop of your script.<br>
begin<br>
     writeln('Setting up include');<br>
end;<br>



