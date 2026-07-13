# Tom Barbalet

I build simulations, games, tools, and small systems that explore how complex worlds can emerge from compact code. Most of my public work sits somewhere between artificial life, cognitive simulation, ecological modeling, historical systems, deterministic game engines, and practical native software. I am especially interested in agent behavior, environment, weather, language, long-running simulation lineages, and the way older ideas can be carried forward through new platforms without losing their original character.

## Noble Ape / ApeSDK

[ApeSDK](https://github.com/barbalet/apesdk), also available at [apesdk.com](https://apesdk.com/) with [documentation](https://apesdk.com/doc/), is the central long-running artificial life line in my public work. I created and maintain the Noble Ape / Simulated Ape simulation, an open source artificial life and cognitive simulation project active since 1996.

The current ApeSDK line is a portable C-centered codebase for autonomous ape-like beings in a changing landscape with weather, biology, movement, memory, language, social relationships, immune behavior, ApeScript, non-polygonal graphics, cached JSON parsing, and native wrappers. Earlier Noble Ape technology was distributed by Apple with new Macs from 2003-2009 and used by Intel from 2005-2011 to test processor mathematical performance. The project has also appeared in academic teaching and research contexts in the US and UK.

Around that core are descendants and support projects: [immersiveape](https://github.com/barbalet/immersiveape), the next incarnation of ApeSDK; [apesdk-rs](https://github.com/barbalet/apesdk-rs), a Rust version; [apesdk-js](https://github.com/barbalet/apesdk-js), a JavaScript port; [longtermbrief](https://github.com/barbalet/longtermbrief), a reduced ApeSDK form for command-line and language-port work; and [skeleton](https://github.com/barbalet/skeleton), a Noble Ape skeleton project.

YouTube video material:

- [Noble Ape Presentation at Intel - Tom Barbalet, July 13, 2010](https://www.youtube.com/watch?v=lbn5F9yBgqw)
- [Nathan Slingerland](https://www.linkedin.com/in/slingn/) and [Sanjay Patel](https://www.linkedin.com/in/sanjay3000/) demonstrating Noble Ape at WWDC 2003: [YouTube](https://www.youtube.com/watch?v=mbQz11RXPFQ)
- [Nathan Slingerland](https://www.linkedin.com/in/slingn/) displaying Noble Ape at the Apple Developer Tools introductory session: [YouTube](https://www.youtube.com/watch?v=iaUkH6bnSFs)

WWDC 2005 had no public Noble Ape video for the Intel implementation, as Apple was much more private about that demonstration.

<p>
  <a href="https://www.youtube.com/watch?v=lbn5F9yBgqw"><img src="https://img.youtube.com/vi/lbn5F9yBgqw/hqdefault.jpg" alt="Noble Ape Presentation at Intel - Tom Barbalet, July 13, 2010" width="260"></a>
  <a href="https://www.youtube.com/watch?v=mbQz11RXPFQ"><img src="https://img.youtube.com/vi/mbQz11RXPFQ/hqdefault.jpg" alt="Nathan Slingerland and Sanjay Patel demonstrating Noble Ape at WWDC 2003" width="260"></a>
  <a href="https://www.youtube.com/watch?v=iaUkH6bnSFs"><img src="https://img.youtube.com/vi/iaUkH6bnSFs/hqdefault.jpg" alt="Nathan Slingerland displaying Noble Ape at the Apple Developer Tools introductory session" width="260"></a>
</p>

## Current Public Work

The newest public work is also represented through [Jagged Seraph](https://jaggedseraph.com/), a public-facing home for current game projects shaped by artificial life, generative AI, and moral play. It currently helps frame newer project directions around [Cage Fighting AI](https://github.com/barbalet/cagefightingai), [Caz](https://github.com/barbalet/caz), and related public project material.

[Cage Fighting AI](https://github.com/barbalet/cagefightingai) is the latest public C simulation. It models identical humanoid cage-fighting robots with the same body, mass, armor, actuator, processor, and component-health rules. The competitive difference is the command program loaded into the head-resident processor. The current simulator has continuous arena positions, velocity, hard-body separation, wall contact, body contact, knockback, downed states, standing recovery, component damage, stoppage rules, and tournament comparison between `.cfos` command sets.

[Caz](https://github.com/barbalet/caz) is a Cat Operating System: a small Z80-inspired virtual machine driving a simulated contemporary house-cat droid. It combines a readable C VM, `.caz` assembly programs, sensor ports, actuator ports, body skills, reflex state, domestic and rural scenarios, and a CazMac native visual path. It is not a cycle-perfect emulator; it keeps the parts that make an 8-bit animal mind feel tangible: registers, flags, bytecode, input/output ports, jumps, and a loop that has to notice the world before deciding what kind of cat it intends to be.

## Tactical And Historical Simulation

The newest public battle-simulation line is the modern urban tactical work around [mosul](https://github.com/barbalet/mosul) and [modernerKrieg](https://github.com/barbalet/modernerKrieg). `mosul` is the Mac SwiftUI project home for a playable tactical demo set around the 2003 Market / Commercial Streets scenario in Mosul, Iraq. `modernerKrieg` is the portable C + CMake tactical engine underneath: deterministic rules, scenario data, asset manifests, board projection, AI/autoplay, replay validation, scoring, headless tests, and native-frontend handoff. Together they focus on urban security problems: line of sight, suppression, wounds, casualties, civilian risk, hidden contacts, suspected threats, rooftop and breach/search interactions, objective control, and platform-native interfaces over shared portable rules.

The recent historical wargame work grew through [guderian](https://github.com/barbalet/guderian), [monty](https://github.com/barbalet/monty), and [derZweiteWeltkrieg](https://github.com/barbalet/derZweiteWeltkrieg). `guderian` is a macOS World War II wargame project about battles connected to Heinz Guderian's field commands, with sober historical framing and a default emphasis on the forces resisting or countering those commands. `monty` applies the same broad design pattern to Bernard Montgomery's field commands, with either side selectable. `derZweiteWeltkrieg` is the underlying playable SwiftUI/C tabletop-style World War II demo, covering force setup, deployment, movement, shooting, artillery, transports, vehicle damage, assaults, morale, objectives, and victory scoring.

[zombie](https://github.com/barbalet/zombie) moves the battle-simulation approach into selected armed engagements from The Troubles, while deliberately excluding attacks on civilians, sectarian killings, punishment attacks, riots, and crowd violence. It uses a bounded tactical scenario model, high-level historical source notes, protected noncombat spaces where needed, and a Mac Catalyst path for scenario browsing and play. [fieldofchaos](https://github.com/barbalet/fieldofchaos) is the tabletop-skirmish rules and engine exploration that informs that work: a traceable C implementation, SwiftUI/Metal app shell, campaign layer, tutorial flow, rule reference, deterministic tests, and release-candidate tooling.

## Other Public Projects

[lastbreach](https://github.com/barbalet/lastbreach) is a post-apocalypse shelter simulation about routine, scarcity, tools, morale, repairs, food, water, and everyday survival after the dramatic event has already happened. [jungle](https://github.com/barbalet/jungle) is a first-person jungle perspective for the Mac. [musictodriveby](https://github.com/barbalet/musictodriveby) is an urban 3D engine. [werewolf](https://github.com/barbalet/werewolf) is a C to Rust, Java, JavaScript, Ruby, and Python transpiler. Its logo was designed by UK artist Stephen "Rochie" Rochfort; the original artwork is [RochieRochfort.jpg](https://github.com/barbalet/werewolf/blob/main/RochieRochfort.jpg). [png2json](https://github.com/barbalet/png2json) turns PNG files into JSON descriptions.

<a href="https://github.com/barbalet/werewolf/blob/main/RochieRochfort.jpg"><img src="https://github.com/barbalet/werewolf/blob/main/RochieRochfort.jpg?raw=true" alt="Werewolf logo artwork by UK artist Stephen Rochie Rochfort" width="260"></a>

The older environmental and historical simulations still matter to the shape of the work. [bronzesim](https://github.com/barbalet/bronzesim) is a stand-alone ISO C99 simulation of an Early Bronze Age-style island world driven by a small domain-specific language. [london1940](https://github.com/barbalet/london1940) simulates London in 1940. They sit beside ApeSDK as part of the same long interest in worlds that can be inspected from the inside: terrain, weather, people, occupations, stress, conflict, and daily life represented through compact rules.

## Working Style

Across these repositories, I tend to favor small, inspectable codebases, portable C foundations, deterministic test surfaces, native Mac interfaces, and systems that can be understood from the inside out. Some repositories are active development work; others are archives, sketches, ports, preserved stages, or public records of a longer line of thought. Together they form a public record of simulation craft: agents, worlds, battles, terrain, cognition, tools, language, and experiments.

For a broader curated index of public work, visit [barbalet.com](https://www.barbalet.com/).
