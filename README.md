# DDS-HAULAGE---MODDING

DDS Haulage
DDS load manager for ETS2 og ATS Truck Simulators (coming)

Hurtig start:

Kopier telemetri dll til "EuroTruckSimulator2 \ bin \ win_x64 \ plugins"

Kør ddsload.exe og ETS2 i enhver rækkefølge

DDS-Cargo-Mod
DDS-Cargo-Mod til ETS2 og ATS Truck Simulators (Coming)

Euro Truck og American Truck Simulators er baseret på simple A-to-B load-and-deliver missioner uden fortællingselementer. DDS Cargo Mod sigter mod at levere værktøjer til at bygge historier oven på spillet. Den grundlæggende ide er at læse telemetri data som lastbil og trailer egenskaber, spillerens verdensposition og at køre en parallel historie afhængig af disse oplysninger. Historien vises i en almindelig webbrowser.

src / vinduer / telemetry_server
Dette program er en telemetri UDP stream klient til Euro Truck Simulator 2 og American Truck Simulator. Det venter på en StoryMod-serverforbindelse og strømmer truckens tilstand og position.

Download telemetri server DLL-filer (TBA) eller bygg fra kilde med Microsoft Visual Studio.

Sæt 32bits DLL i bin / win_x86 / plugins / eller 64bits DLL i bin / win_x64 / plugins / afhængigt af om du vil afspille 32 eller 64 bit. Hvis du vil bruge StoryMod med Multiplayer Mod, skal du bruge 32bits-versionen.

Få IP til denne maskine, du skal bruge den til at køre serveren.

Start spillet før ddsmod-serveren. Når du er i stand til at køre, skal du starte serveren.









ENGLISH VERSION:









DDS HAULAGE --- Modding
DDS Haulage DDS load manager for ETS2 and ATS Truck Simulators (coming)

Quick Start:

Copy telemetry dll to "EuroTruckSimulator2 \ bin \ win_x64 \ plugins"

Run ddsload.exe and ETS2 in any order

DDS-Cargo-Mod DDS-Cargo Mod for ETS2 and ATS Truck Simulators (Coming)

Euro Truck and American Truck Simulators are based on simple A-to-B load-and-deliver missions without telling elements. DDS Cargo Mod aims to provide tools for building stories on the game. The basic idea is to read telemetry data like truck and trailer properties, the player's world position and run a parallel story depending on this information. The story is displayed in a regular web browser.

src / windows / telemetry_server This program is a telemetry UDP stream client for Euro Truck Simulator 2 and American Truck Simulator. It is waiting for a StoryMod server connection and flows the state and position of the truck.

Download telemetry server DLL files (TBA) or build from source with Microsoft Visual Studio.

Put 32bits DLL into bin / win_x86 / plugins / or 64bits DLL in bin / win_x64 / plugins / depending on whether you want to play 32 or 64 bit. To use StoryMod with Multiplayer Mod, use the 32bits version.

Get IP to this machine, you need it to run the server.

Start game before ddsmod server. When you are able to drive, start the server.

