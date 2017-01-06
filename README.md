# BlankSrl-6
The srl-6 without all the pre-built RS functions,  So makes for a perect base for any RSPS<br>
This is the base to my runique include, so use this look in the scripts folder at test.simba to see on how to inlcude this. <br>
All though,if you want to add more functionality you will have to create a new simba file and add it to srl.simba file.<br>
Like so<br>
Current srl.simba<br>
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

<strong>{$include_once location/example.simba} -add this line </strong> <br>

procedure SetupRSPSinclude;<br>
begin<br>
     writeln('Setting up include');<br>
end;<br>

To add a file to srl.simba add example line below all the other include onece files and just repeat as needed<br>
<strong>{$include_once location/example.simba}</strong> <br>

