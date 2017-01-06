# BlankSrl-6
The srl-6 without all the pre-built RS functions,  So makes for a perect base for any RSPS<br>
To use this include, download and  extract it in your simba/includes directory and rename it to just BlankSrl-6 or the rsps your using it for and adjust the line below to the new name.<br>
Then add this to the top  of the script you want to use it on. {$i BlankSrl-6/srl.simba} <br>
All though,if you want to add more functionality, you will have to create  new simba files and add them to the srl.simba file.<br>
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

To add a file to srl.simba add the example line below, below all the other include once files and just repeat as needed<br>
<strong>{$include_once location/example.simba}</strong> <br>

