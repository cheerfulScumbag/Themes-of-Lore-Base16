# Themes of Lore (Base16)

A collection of custom Base16 themes inspired by nature. Each theme includes dark and light variants.

## Available Themes

Explore the embedded previews below showcasing the colors in action!

### Burning Ocean

<style>
.burning-ocean-preview {
  --base00: #023047;
  --base01: #0a4c6a;
  --base02: #126782;
  --base03: #219ebc;
  --base04: #58b4d1;
  --base05: #73bfdc;
  --base06: #8ecae6;
  --base07: #d5f2ff;
  --base08: #fb8500;
  --base09: #fd9e02;
  --base0A: #ffb703;
  --base0B: #8ecae6;
  --base0C: #fb9017;
  --base0D: #ffb703;
  --base0E: #bb3e03;
  --base0F: #9b2226;
}
.burning-ocean-preview h1 {
  color: var(--base0D);
  margin-bottom: 10px;
  font-weight: 300;
  text-align: center;
}
.burning-ocean-preview .window {
  background-color: var(--base00);
  border: 1px solid var(--base02);
  border-radius: 12px;
  box-shadow: 0 20px 50px rgba(2, 48, 71, 0.8), 0 0 40px rgba(255, 183, 3, 0.1);
  overflow: hidden;
  width: 100%;
  max-width: 800px;
}
.burning-ocean-preview .titlebar {
  background-color: var(--base01);
  padding: 12px 18px;
  display: flex;
  gap: 8px;
  border-bottom: 1px solid var(--base02);
}
.burning-ocean-preview .mac-btn {
  width: 13px;
  height: 13px;
  border-radius: 50%;
}
.burning-ocean-preview .close {
  background-color: var(--base08);
}
.burning-ocean-preview .min {
  background-color: var(--base0A);
}
.burning-ocean-preview .max {
  background-color: var(--base0B);
}
.burning-ocean-preview pre {
  padding: 25px;
  margin: 0;
  font-size: 16px;
  line-height: 1.6;
  overflow-x: auto;
  background-color: var(--base00);
  color: var(--base05);
  font-family: 'Fira Code', 'Cascadia Code', Consolas, monospace;
}
.burning-ocean-preview .keyword {
  color: var(--base0E);
  font-weight: bold;
}
.burning-ocean-preview .function {
  color: var(--base0D);
}
.burning-ocean-preview .string {
  color: var(--base0B);
}
.burning-ocean-preview .number {
  color: var(--base09);
}
.burning-ocean-preview .comment {
  color: var(--base03);
  font-style: italic;
}
.burning-ocean-preview .class {
  color: var(--base0A);
}
.burning-ocean-preview .operator {
  color: var(--base05);
}
.burning-ocean-preview .variable {
  background-color: var(--base08);
}
.burning-ocean-preview .regex {
  color: var(--base0C);
}
.burning-ocean-preview .property {
  color: var(--base08);
}
.burning-ocean-preview .deprecated {
  color: var(--base0F);
  text-decoration: line-through;
}
</style>
<div class="burning-ocean-preview">
<h1>Burning Ocean - Deep Water Fire</h1>
<div class="window">
<div class="titlebar">
<div class="mac-btn close"></div>
<div class="mac-btn min"></div>
<div class="mac-btn max"></div>
</div>
<pre><code><span class="comment"># Burning Ocean - Elemental balance of fire & water</span>
import re
from typing import List
class ElementalSynth:
    def __init__(self, intensity: int = 100):
        self.intensity = intensity
        self.is_active = True
        self.element = "Burning Water"
    def ignite_waves(self, layer: str) -> bool:
        # Cast fire upon the deep sea
        if not self.is_active:
            return False
        regex_pattern = r"^current_\d+$"
        if re.match(regex_pattern, layer):
            print(f"Igniting layer: {layer} at intensity {self.intensity}")
            return True
            
        return False
        
    def extinguished_method(self):
        <span class="deprecated">return "This is Base0F"</span></code></pre>
</div>
</div>

### Enchanted Midnight

<style>
.enchanted-midnight-preview {
  --base00: #180034;
  --base01: #2e005d;
  --base02: #450074;
  --base03: #5c008b;
  --base04: #75008b;
  --base05: #a37ac3;
  --base06: #d1b3e8;
  --base07: #f2e6fa;
  --base08: #8e008b;
  --base09: #ff6200;
  --base0A: #ff8300;
  --base0B: #327a5d;
  --base0C: #369ba3;
  --base0D: #bf75d6;
  --base0E: #f0567a;
  --base0F: #d62828;
}
.enchanted-midnight-preview h1 {
  color: var(--base08);
  margin-bottom: 10px;
  font-weight: 300;
  text-align: center;
  text-shadow: 0 0 10px rgba(142, 0, 139, 0.4);
}
.enchanted-midnight-preview .window {
  background-color: var(--base00);
  border: 1px solid var(--base01);
  border-radius: 12px;
  box-shadow: 0 20px 50px rgba(24, 0, 52, 0.9), 0 0 40px rgba(142, 0, 139, 0.1);
  overflow: hidden;
  width: 100%;
  max-width: 800px;
}
.enchanted-midnight-preview .titlebar {
  background-color: var(--base01);
  padding: 12px 18px;
  display: flex;
  gap: 8px;
  border-bottom: 1px solid var(--base02);
}
.enchanted-midnight-preview .mac-btn {
  width: 13px;
  height: 13px;
  border-radius: 50%;
}
.enchanted-midnight-preview .close {
  background-color: var(--base08);
}
.enchanted-midnight-preview .min {
  background-color: var(--base0A);
}
.enchanted-midnight-preview .max {
  background-color: var(--base0B);
}
.enchanted-midnight-preview pre {
  padding: 25px;
  margin: 0;
  font-size: 16px;
  line-height: 1.6;
  overflow-x: auto;
  background-color: var(--base00);
  color: var(--base05);
  font-family: 'Fira Code', 'Cascadia Code', Consolas, monospace;
}
.enchanted-midnight-preview .keyword {
  color: var(--base0E);
  font-weight: bold;
}
.enchanted-midnight-preview .function {
  color: var(--base0D);
}
.enchanted-midnight-preview .string {
  color: var(--base0B);
}
.enchanted-midnight-preview .number {
  color: var(--base09);
}
.enchanted-midnight-preview .comment {
  color: var(--base03);
  font-style: italic;
}
.enchanted-midnight-preview .class {
  color: var(--base0A);
}
.enchanted-midnight-preview .operator {
  color: var(--base05);
}
.enchanted-midnight-preview .variable {
  color: var(--base08);
}
.enchanted-midnight-preview .regex {
  color: var(--base0C);
}
.enchanted-midnight-preview .property {
  color: var(--base08);
}
.enchanted-midnight-preview .deprecated {
  color: var(--base0F);
  text-decoration: line-through;
}
</style>
<div class="enchanted-midnight-preview">
<h1>Enchanted Midnight - The Edge of the World</h1>
<div class="window">
<div class="titlebar">
<div class="mac-btn close"></div>
<div class="mac-btn min"></div>
<div class="mac-btn max"></div>
</div>
<pre><code><span class="comment"># Enchanted Midnight - We are the last humans on earth.</span>
import stillness
from horizon import View
class CliffEdge:
    def __init__(self, fear: int = 0):
        self.fear = fear
        self.is_calm = True
        self.sky = "Deep, deep purple."
    def look_at_horizon(self, view: str) -> bool:
        # Look at that view.
        if self.fear > 0:
            return False
        regex_pattern = r"^glowing_embers_\d+$"
        if re.match(regex_pattern, view):
            print(f"Witnessing: {view}. We are alone.")
            return True
            
        return False
        
    def panic(self):
        <span class="deprecated">return "This is Base0F"</span></code></pre>
</div>
</div>

### Funky Pigeon

<style>
.funky-pigeon-preview {
  --base00: #1b1e23;
  --base01: #23272e;
  --base02: #2c313a;
  --base03: #3e4451;
  --base04: #565c64;
  --base05: #abb2bf;
  --base06: #c8ccd4;
  --base07: #e0e3e8;
  --base08: #f2636a;
  --base09: #ef6803;
  --base0A: #c1b225;
  --base0B: #72a85f;
  --base0C: #36a7a2;
  --base0D: #229e99;
  --base0E: #e94900;
  --base0F: #c63333;
}
.funky-pigeon-preview h1 {
  color: var(--base0D);
  margin-bottom: 10px;
  font-weight: 300;
  text-align: center;
}
.funky-pigeon-preview .window {
  background-color: var(--base00);
  border: 1px solid var(--base02);
  border-radius: 12px;
  box-shadow: 0 20px 50px rgba(27, 30, 35, 0.8), 0 0 30px rgba(242, 99, 106, 0.1);
  overflow: hidden;
  width: 100%;
  max-width: 800px;
}
.funky-pigeon-preview .titlebar {
  background-color: var(--base01);
  padding: 12px 18px;
  display: flex;
  gap: 8px;
  border-bottom: 1px solid var(--base02);
}
.funky-pigeon-preview .mac-btn {
  width: 13px;
  height: 13px;
  border-radius: 50%;
}
.funky-pigeon-preview .close {
  background-color: var(--base08);
}
.funky-pigeon-preview .min {
  background-color: var(--base0A);
}
.funky-pigeon-preview .max {
  background-color: var(--base0B);
}
.funky-pigeon-preview pre {
  padding: 25px;
  margin: 0;
  font-size: 16px;
  line-height: 1.6;
  overflow-x: auto;
  background-color: var(--base00);
  color: var(--base05);
  font-family: 'Fira Code', 'Cascadia Code', Consolas, monospace;
}
.funky-pigeon-preview .keyword {
  color: var(--base0E);
  font-weight: bold;
}
.funky-pigeon-preview .function {
  color: var(--base0D);
}
.funky-pigeon-preview .string {
  color: var(--base0B);
}
.funky-pigeon-preview .number {
  color: var(--base09);
}
.funky-pigeon-preview .comment {
  color: var(--base03);
  font-style: italic;
}
.funky-pigeon-preview .class {
  color: var(--base0A);
}
.funky-pigeon-preview .operator {
  color: var(--base05);
}
.funky-pigeon-preview .variable {
  color: var(--base08);
}
.funky-pigeon-preview .regex {
  color: var(--base0C);
}
.funky-pigeon-preview .property {
  color: var(--base08);
}
.funky-pigeon-preview .deprecated {
  color: var(--base0F);
  text-decoration: line-through;
}
</style>
<div class="funky-pigeon-preview">
<h1>Funky Pigeon - Retro Avionics</h1>
<div class="window">
<div class="titlebar">
<div class="mac-btn close"></div>
<div class="mac-btn min"></div>
<div class="mac-btn max"></div>
</div>
<pre><code><span class="comment"># Funky Pigeon - Iridescent accents on a stormy gray</span>
import re
from typing import List
class RetroSynth:
    def __init__(self, groovy: bool = True):
        self.groovy = groovy
        self.is_active = True
        self.vibe = "Iridescent Flyby"
    def play_track(self, title: str) -> bool:
        # A funky beat from the 70s
        if not self.is_active:
            return False
        regex_pattern = r"^track_\d+$"
        if re.match(regex_pattern, title):
            print(f"Now playing: {title} (Groovy? {self.groovy})")
            return True
            
        return False
        
    def old_boring_method(self):
        <span class="deprecated">return "This is Base0F"</span></code></pre>
</div>
</div>

### Maladaptive Tangerine

<style>
.maladaptive-tangerine-preview {
  --base00: #001219;
  --base01: #005f73;
  --base02: #0a9396;
  --base03: #126782;
  --base04: #219ebc;
  --base05: #58b4d1;
  --base06: #73bfdc;
  --base07: #8ecae6;
  --base08: #9b2226;
  --base09: #bb3e03;
  --base0A: #ca6702;
  --base0B: #94d2bd;
  --base0C: #e9d8a6;
  --base0D: #ee9b00;
  --base0E: #fb8500;
  --base0F: #ae2012;
}
.maladaptive-tangerine-preview h1 {
  color: var(--base0D);
  margin-bottom: 10px;
  font-weight: 300;
  text-align: center;
}
.maladaptive-tangerine-preview .window {
  background-color: var(--base00);
  border: 1px solid var(--base02);
  border-radius: 12px;
  box-shadow: 0 20px 50px rgba(0, 18, 25, 0.9), 0 0 30px rgba(238, 155, 0, 0.2);
  overflow: hidden;
  width: 100%;
  max-width: 800px;
}
.maladaptive-tangerine-preview .titlebar {
  background-color: var(--base01);
  padding: 12px 18px;
  display: flex;
  gap: 8px;
  border-bottom: 1px solid var(--base02);
}
.maladaptive-tangerine-preview .mac-btn {
  width: 13px;
  height: 13px;
  border-radius: 50%;
}
.maladaptive-tangerine-preview .close {
  background-color: var(--base08);
}
.maladaptive-tangerine-preview .min {
  background-color: var(--base0A);
}
.maladaptive-tangerine-preview .max {
  background-color: var(--base0B);
}
.maladaptive-tangerine-preview pre {
  padding: 25px;
  margin: 0;
  font-size: 16px;
  line-height: 1.6;
  overflow-x: auto;
  background-color: var(--base00);
  color: var(--base05);
  font-family: 'Fira Code', 'Cascadia Code', Consolas, monospace;
}
.maladaptive-tangerine-preview .keyword {
  color: var(--base0E);
  font-weight: bold;
}
.maladaptive-tangerine-preview .function {
  color: var(--base0D);
}
.maladaptive-tangerine-preview .string {
  color: var(--base0B);
}
.maladaptive-tangerine-preview .number {
  color: var(--base09);
}
.maladaptive-tangerine-preview .comment {
  color: var(--base03);
  font-style: italic;
}
.maladaptive-tangerine-preview .class {
  color: var(--base0A);
}
.maladaptive-tangerine-preview .operator {
  color: var(--base05);
}
.maladaptive-tangerine-preview .variable {
  color: var(--base08);
}
.maladaptive-tangerine-preview .regex {
  color: var(--base0C);
}
.maladaptive-tangerine-preview .property {
  color: var(--base08);
}
.maladaptive-tangerine-preview .deprecated {
  color: var(--base0F);
  text-decoration: line-through;
}
</style>
<div class="maladaptive-tangerine-preview">
<h1>Maladaptive Tangerine - Island Night Terrors</h1>
<div class="window">
<div class="titlebar">
<div class="mac-btn close"></div>
<div class="mac-btn min"></div>
<div class="mac-btn max"></div>
</div>
<pre><code><span class="comment"># Maladaptive Tangerine - A fever dream in the tropics</span>
import re
from typing import List
class TropicalNightmare:
    def __init__(self, hallucinations: int = 999):
        self.hallucinations = hallucinations
        self.is_sweating = True
        self.symptom = "Pale Poison Green Leaves"
    def wander_jungle(self, path: str) -> bool:
        # The tangerines are screaming
        if not self.is_sweating:
            return False
        regex_pattern = r"^shadow_\d+$"
        if re.match(regex_pattern, path):
            print(f"Lost in: {path} (Hallucinations: {self.hallucinations})")
            return True
            
        return False
        
    def dried_blood_method(self):
        <span class="deprecated">return "This is Base0F"</span></code></pre>
</div>
</div>

### Nature's Power

<style>
.natures-power-preview {
  --base00: #140c09;
  --base01: #2a1913;
  --base02: #43291f;
  --base03: #5e3f32;
  --base04: #805b4b;
  --base05: #b39a8c;
  --base06: #d6c8bd;
  --base07: #f4f0bb;
  --base08: #da2c38;
  --base09: #f26457;
  --base0A: #ccb147;
  --base0B: #87c38f;
  --base0C: #226f54;
  --base0D: #ab3f46;
  --base0E: #a0cfa5;
  --base0F: #6b2f28;
}
.natures-power-preview h1 {
  color: var(--base08);
  margin-bottom: 10px;
  font-weight: 300;
  text-align: center;
  text-shadow: 0 0 10px rgba(218, 44, 56, 0.4);
}
.natures-power-preview .window {
  background-color: var(--base00);
  border: 1px solid var(--base02);
  border-radius: 12px;
  box-shadow: 0 20px 50px rgba(20, 12, 9, 0.9), 0 0 40px rgba(135, 195, 143, 0.1);
  overflow: hidden;
  width: 100%;
  max-width: 800px;
}
.natures-power-preview .titlebar {
  background-color: var(--base01);
  padding: 12px 18px;
  display: flex;
  gap: 8px;
  border-bottom: 1px solid var(--base02);
}
.natures-power-preview .mac-btn {
  width: 13px;
  height: 13px;
  border-radius: 50%;
}
.natures-power-preview .close {
  background-color: var(--base08);
}
.natures-power-preview .min {
  background-color: var(--base0A);
}
.natures-power-preview .max {
  background-color: var(--base0B);
}
.natures-power-preview pre {
  padding: 25px;
  margin: 0;
  font-size: 16px;
  line-height: 1.6;
  overflow-x: auto;
  background-color: var(--base00);
  color: var(--base05);
  font-family: 'Fira Code', 'Cascadia Code', Consolas, monospace;
}
.natures-power-preview .keyword {
  color: var(--base0E);
  font-weight: bold;
}
.natures-power-preview .function {
  color: var(--base0D);
}
.natures-power-preview .string {
  color: var(--base0B);
}
.natures-power-preview .number {
  color: var(--base09);
}
.natures-power-preview .comment {
  color: var(--base03);
  font-style: italic;
}
.natures-power-preview .class {
  color: var(--base0A);
}
.natures-power-preview .operator {
  color: var(--base05);
}
.natures-power-preview .variable {
  color: var(--base08);
}
.natures-power-preview .regex {
  color: var(--base0C);
}
.natures-power-preview .property {
  color: var(--base08);
}
.natures-power-preview .deprecated {
  color: var(--base0F);
  text-decoration: line-through;
}
</style>
<div class="natures-power-preview">
<h1>Nature's Power - The Deep Woods</h1>
<div class="window">
<div class="titlebar">
<div class="mac-btn close"></div>
<div class="mac-btn min"></div>
<div class="mac-btn max"></div>
</div>
<pre><code><span class="comment"># Nature's Power - Frightening, eerie folklore of the wild</span>
import sacrifices
from deep_earth import Roots
class AncientGrove:
    def __init__(self, warnings: int = 3):
        self.warnings = warnings
        self.is_watching = True
        self.folklore = "Do not stray from the path."
    def enter_woods(self, offering: str) -> bool:
        # Complex and fascinating roles these elements play
        if self.warnings <= 0:
            return False
        regex_pattern = r"^crimson_stain_\d+$"
        if re.match(regex_pattern, offering):
            print(f"The roots accept: {offering}. Heed the folklore.")
            return True
            
        return False
        
    def wither(self):
        <span class="deprecated">return "This is Base0F"</span></code></pre>
</div>
</div>

### Tango

<style>
.tango-preview {
  --base00: #17262D;
  --base01: #1C2E37;
  --base02: #394B53;
  --base03: #56676F;
  --base04: #89959B;
  --base05: #BCC3C7;
  --base06: #D6DADD;
  --base07: #EFF1F3;
  --base08: #FF4000;
  --base09: #FF7B00;
  --base0A: #FFB733;
  --base0B: #fbff00;
  --base0C: #FF2A55;
  --base0D: #FFDEB3;
  --base0E: #E60033;
  --base0F: #992600;
}
.tango-preview h1 {
  color: var(--base0D);
  margin-bottom: 10px;
  font-weight: 300;
  text-align: center;
}
.tango-preview .window {
  background-color: var(--base00);
  border: 1px solid var(--base02);
  border-radius: 12px;
  box-shadow: 0 20px 50px rgba(0, 0, 0, 0.6);
  overflow: hidden;
  width: 100%;
  max-width: 800px;
}
.tango-preview .titlebar {
  background-color: var(--base01);
  padding: 12px 18px;
  display: flex;
  gap: 8px;
  border-bottom: 1px solid var(--base02);
}
.tango-preview .mac-btn {
  width: 13px;
  height: 13px;
  border-radius: 50%;
}
.tango-preview .close {
  background-color: var(--base08);
}
.tango-preview .min {
  background-color: var(--base0A);
}
.tango-preview .max {
  background-color: var(--base0B);
}
.tango-preview pre {
  padding: 25px;
  margin: 0;
  font-size: 16px;
  line-height: 1.6;
  overflow-x: auto;
  background-color: var(--base00);
  color: var(--base05);
  font-family: 'Fira Code', 'Cascadia Code', Consolas, monospace;
}
.tango-preview .keyword {
  color: var(--base0E);
  font-weight: bold;
}
.tango-preview .function {
  color: var(--base0D);
}
.tango-preview .string {
  color: var(--base0B);
}
.tango-preview .number {
  color: var(--base09);
}
.tango-preview .comment {
  color: var(--base03);
  font-style: italic;
}
.tango-preview .class {
  color: var(--base0A);
}
.tango-preview .operator {
  color: var(--base05);
}
.tango-preview .variable {
  color: var(--base08);
}
.tango-preview .regex {
  color: var(--base0C);
}
.tango-preview .property {
  color: var(--base08);
}
.tango-preview .deprecated {
  color: var(--base0F);
  text-decoration: line-through;
}
</style>
<div class="tango-preview">
<h1>Tango Dark - 80s Metallic Fire</h1>
<div class="window">
<div class="titlebar">
<div class="mac-btn close"></div>
<div class="mac-btn min"></div>
<div class="mac-btn max"></div>
</div>
<pre><code><span class="comment"># Tango Theme - 80s Orange & Red Metallic scheme</span>
import re
from typing import List
class SynthWaveGenerator:
    def __init__(self, volume: int = 11):
        self.volume = volume
        self.is_active = True
        self.style = "Metallic Fire"
    def play_track(self, title: str) -> bool:
        # Play the track with intense neon colors
        if not self.is_active:
            return False
        regex_pattern = r"^track_\d+$"
        if re.match(regex_pattern, title):
            print(f"Now playing: {title} at volume {self.volume}")
            return True
            
        return False
        
    def old_method_do_not_use(self):
        <span class="deprecated">return "This is Base0F"</span></code></pre>
</div>
</div>

### Taste of Italy

<style>
.taste-of-italy-preview {
  --base00: #240000;
  --base01: #3b0808;
  --base02: #5c0000;
  --base03: #751717;
  --base04: #ba0c0c;
  --base05: #ffebeb;
  --base06: #ecffeb;
  --base07: #ffffff;
  --base08: #ff0000;
  --base09: #ba0c0c;
  --base0A: #2a850e;
  --base0B: #27a300;
  --base0C: #ecffeb;
  --base0D: #ffebeb;
  --base0E: #005c00;
  --base0F: #2d661b;
}
.taste-of-italy-preview h1 {
  color: var(--base08);
  margin-bottom: 10px;
  font-weight: 300;
  text-align: center;
}
.taste-of-italy-preview .window {
  background-color: var(--base00);
  border: 1px solid var(--base02);
  border-radius: 12px;
  box-shadow: 0 20px 50px rgba(36, 0, 0, 0.8), 0 0 40px rgba(255, 0, 0, 0.1);
  overflow: hidden;
  width: 100%;
  max-width: 800px;
}
.taste-of-italy-preview .titlebar {
  background-color: var(--base01);
  padding: 12px 18px;
  display: flex;
  gap: 8px;
  border-bottom: 1px solid var(--base02);
}
.taste-of-italy-preview .mac-btn {
  width: 13px;
  height: 13px;
  border-radius: 50%;
}
.taste-of-italy-preview .close {
  background-color: var(--base08);
}
.taste-of-italy-preview .min {
  background-color: var(--base0A);
}
.taste-of-italy-preview .max {
  background-color: var(--base0B);
}
.taste-of-italy-preview pre {
  padding: 25px;
  margin: 0;
  font-size: 16px;
  line-height: 1.6;
  overflow-x: auto;
  background-color: var(--base00);
  color: var(--base05);
  font-family: 'Fira Code', 'Cascadia Code', Consolas, monospace;
}
.taste-of-italy-preview .keyword {
  color: var(--base0E);
  font-weight: bold;
}
.taste-of-italy-preview .function {
  color: var(--base0D);
}
.taste-of-italy-preview .string {
  color: var(--base0B);
}
.taste-of-italy-preview .number {
  color: var(--base09);
}
.taste-of-italy-preview .comment {
  color: var(--base03);
  font-style: italic;
}
.taste-of-italy-preview .class {
  color: var(--base0A);
}
.taste-of-italy-preview .operator {
  color: var(--base05);
}
.taste-of-italy-preview .variable {
  color: var(--base08);
}
.taste-of-italy-preview .regex {
  color: var(--base0C);
}
.taste-of-italy-preview .property {
  color: var(--base08);
}
.taste-of-italy-preview .deprecated {
  color: var(--base0F);
  text-decoration: line-through;
}
</style>
<div class="taste-of-italy-preview">
<h1>Taste of Italy - Il Pomodoro</h1>
<div class="window">
<div class="titlebar">
<div class="mac-btn close"></div>
<div class="mac-btn min"></div>
<div class="mac-btn max"></div>
</div>
<pre><code><span class="comment"># Taste of Italy - A culinary experience in code</span>
import re
from typing import List
class Trattoria:
    def __init__(self, servings: int = 4):
        self.servings = servings
        self.is_cooking = True
        self.dish = "Pasta al Pomodoro con Basilico"
    def prepare_sauce(self, ingredient: str) -> bool:
        # Add the fresh basil to the rich tomato sauce
        if not self.is_cooking:
            return False
        regex_pattern = r"^tomato_\d+$"
        if re.match(regex_pattern, ingredient):
            print(f"Adding ingredient: {ingredient} for {self.servings} people")
            return True
            
        return False
        
    def stale_bread(self):
        <span class="deprecated">return "This is Base0F"</span></code></pre>
</div>
</div>

### Twilight Harvest

<style>
.twilight-harvest-preview {
  --base00: #13232c;
  --base01: #1d323f;
  --base02: #233d4d;
  --base03: #455f71;
  --base04: #70899c;
  --base05: #a3b9c8;
  --base06: #dce6ed;
  --base07: #f0f5f9;
  --base08: #cc5200;
  --base09: #d9651c;
  --base0A: #e0ad1b;
  --base0B: #a1c181;
  --base0C: #7a9b5b;
  --base0D: #fcca46;
  --base0E: #c4cf4b;
  --base0F: #a63f00;
}
.twilight-harvest-preview h1 {
  color: var(--base0D);
  margin-bottom: 10px;
  font-weight: 300;
  text-align: center;
}
.twilight-harvest-preview .window {
  background-color: var(--base00);
  border: 1px solid var(--base01);
  border-radius: 12px;
  box-shadow: 0 20px 50px rgba(19, 35, 44, 0.9), 0 0 40px rgba(254, 127, 45, 0.05);
  overflow: hidden;
  width: 100%;
  max-width: 800px;
}
.twilight-harvest-preview .titlebar {
  background-color: var(--base02);
  padding: 12px 18px;
  display: flex;
  gap: 8px;
  border-bottom: 1px solid var(--base01);
}
.twilight-harvest-preview .mac-btn {
  width: 13px;
  height: 13px;
  border-radius: 50%;
}
.twilight-harvest-preview .close {
  background-color: var(--base08);
}
.twilight-harvest-preview .min {
  background-color: var(--base0A);
}
.twilight-harvest-preview .max {
  background-color: var(--base0B);
}
.twilight-harvest-preview pre {
  padding: 25px;
  margin: 0;
  font-size: 16px;
  line-height: 1.6;
  overflow-x: auto;
  background-color: var(--base00);
  color: var(--base05);
  font-family: 'Fira Code', 'Cascadia Code', Consolas, monospace;
}
.twilight-harvest-preview .keyword {
  color: var(--base0E);
  font-weight: bold;
}
.twilight-harvest-preview .function {
  color: var(--base0D);
}
.twilight-harvest-preview .string {
  color: var(--base0B);
}
.twilight-harvest-preview .number {
  color: var(--base09);
}
.twilight-harvest-preview .comment {
  color: var(--base03);
  font-style: italic;
}
.twilight-harvest-preview .class {
  color: var(--base0A);
}
.twilight-harvest-preview .operator {
  color: var(--base05);
}
.twilight-harvest-preview .variable {
  color: var(--base08);
}
.twilight-harvest-preview .regex {
  color: var(--base0C);
}
.twilight-harvest-preview .property {
  color: var(--base08);
}
.twilight-harvest-preview .deprecated {
  color: var(--base0F);
  text-decoration: line-through;
}
</style>
<div class="twilight-harvest-preview">
<h1>Twilight Harvest - The Brewing Storm</h1>
<div class="window">
<div class="titlebar">
<div class="mac-btn close"></div>
<div class="mac-btn min"></div>
<div class="mac-btn max"></div>
</div>
<pre><code><span class="comment"># Twilight Harvest - Almost late for the harvest, the rain is about to start...</span>
import sys
from forecast import Storm
class AutumnField:
    def __init__(self, pumpkins: int = 42):
        self.pumpkins = pumpkins
        self.is_raining = False
        self.weather = "Heavy clouds gathering"
    def gather_crops(self, urgency: str) -> bool:
        # We need to hurry before the storm breaks
        if self.is_raining:
            return False
        regex_pattern = r"^thunder_\d+$"
        if re.match(regex_pattern, urgency):
            print(f"Warning: {urgency} detected. {self.pumpkins} crops remaining!")
            return True
            
        return False
        
    def withered_vine(self):
        <span class="deprecated">return "This is Base0F"</span></code></pre>
</div>
</div>

* **Deep Sea Synthwave** - [Preview](deep-sea-synthwave/deep-sea-synthwave-preview.html)
* **Green Tea & Cheesecake** - [Preview](green-tea-cheesecake/green-tea-cheesecake-preview.html)

## How to Use

Each directory contains:
- `[theme-name]-dark.yaml` (Base16 Dark Scheme)
- `[theme-name]-light.yaml` (Base16 Light Scheme)
- `[theme-name]-preview.html` (Interactive HTML visualizer)

These schemes can be used with any Base16 builder to generate themes for your favorite applications (terminals, editors, UI elements).