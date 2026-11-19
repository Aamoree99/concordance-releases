# Client documentation dependency

Markdig 1.4.2 — https://github.com/xoofx/markdig — BSD-2-Clause.
Used to parse the bundled GDD Markdown; no custom Markdown parser is implemented.
Godot and the existing simulation dependencies retain their own distributions and licenses.

Copyright (c) 2016-2026, Alexandre Mutel
All rights reserved.

Redistribution and use in source and binary forms, with or without modification
, are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright notice, this
   list of conditions and the following disclaimer.

2. Redistributions in binary form must reproduce the above copyright notice,
   this list of conditions and the following disclaimer in the documentation
   and/or other materials provided with the distribution.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND
ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED
WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE
FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL
DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR
SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER
CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY,
OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.


## Lucide navigation icons

https://github.com/lucide-icons/lucide — revision 7faf87628a1ad6175975bc595344337ce14a7db4.
ISC/MIT license reproduced in Assets/Icons/Lucide/LICENSE. Navigation, resource and strategic fleet SVGs; currentColor replaced with white for Godot modulation.

## Main menu parallax art

Assets/Menu/layers: Space 4X "Atmospheric Minimalism" parallax pack, original flat-vector artwork produced for this project;
no third-party artwork or text is embedded.

## System screen sprites

Assets/System: "Space 4X menu-matched atmospheric sprite set v2" — original artwork produced for this project; no third-party artwork or text is embedded.
Assets/Atlas: "Atmospheric Atlas Parallax v0.3" background layers, same provenance.
Assets/Atlas/Map: "Atlas Map Background v0.4 (EVE-inspired Atmospheric Minimalism)" — seven seamless 2048 px layers and the layer manifest; original artwork produced for this project
(composition-only inspiration, no third-party pixels); `galaxy_backdrop.gdshader` is derived from the pack's own sample shader with an added dither pass.

Additional Lucide icons (factory, zap, truck, telescope, shield, circle-check, loader-circle, circle, lock, mail, radio, users, bell, scale, triangle-alert, globe,
satellite-dish, fuel, circle-dashed, hourglass, check) were exported from the lucide npm package v1.8.0 (ISC), same licence and white-stroke treatment as above.

## Interface fonts

Exo 2 — Copyright 2013 The Exo 2 Project Authors (https://github.com/googlefonts/Exo-2.0). Onest — Copyright 2021 The Onest Project Authors (https://github.com/simpals/onest). Both distributed under SIL Open Font License 1.1; complete licenses are packaged alongside the unmodified variable fonts in `Assets/Fonts/{Exo2,Onest}/OFL.txt`. No creator credit is required in the main game UI. Font provenance, checksums and roles: `docs/UI_VISUAL_SYSTEM.md` in the source repository.

## Additional components in the desktop builds

- Godot Engine and GodotSharp 4.7.2 — [license](licenses/Godot-LICENSE.txt) and [engine copyright notices](licenses/Godot-COPYRIGHT.txt).
- Microsoft .NET 8 Runtime — [license](licenses/dotnet-LICENSE.txt) and [third-party notices](licenses/dotnet-THIRD-PARTY-NOTICES.txt).
- Newtonsoft.Json 13.0.3 — [license](licenses/Newtonsoft.Json.txt).
- Humanizer.Core 2.14.1 — [license](licenses/Humanizer.txt).
- JsonSchema.Net 9.4.1, JsonPointer.Net 7.0.3 and Json.More.Net 3.0.1 — [project license](licenses/Json-Everything-LICENSE.txt) and [binary terms](licenses/Json-Everything-binary-terms.txt).
- [Lucide](licenses/Lucide.txt), [Exo 2](licenses/Exo2-OFL.txt) and [Onest](licenses/Onest-OFL.txt) notices.
