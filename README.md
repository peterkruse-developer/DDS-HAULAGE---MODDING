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

