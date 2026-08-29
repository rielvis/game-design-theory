# P1-STEP 1 : Mechanics Design
The mechanics design of your GDD is the detailing how the game works as a system. This step also goes into player dynamics design and what motivates a player to actually play.

Deliverables for this step are:
- _Game Dynamics Overview w/ Motivation & Flow-State Considerations_
- _Mechanical Systems Blueprint (according to game dynamics specifications)_
- _Playable Prototype w/ Core Systems_

---

## Mechanics & Game Systems
Game mechanics are the systems and rules that govern how the game operates in order to build the abstract illusion of gameplay being sold to the player. It describes the granular workings of the game in a network of inputs, conditions, and outputs.

As the naming would suggest, game mechanic design looks at games in a purely and atomically mechanical “if-then” manner. In the same way a car mechanic looks at cars as a multitude of granular systems rather than a single vehicular unit, game mechanics have a very architectural ethic towards games.

## Dynamics & Player Motivations
Game dynamics describe how the player may behave in response to the game mechanics. Based on the information the player has about the game and what the rules allow them to do, there are certain behaviours the player may exhibit.

Though, how exactly they behave depends on what motivates them to play.

| Action | Social | Mastery | Achievement | Immersion | Creation |
|-|-|-|-|-|-|
| Destruction | Competition | Challenge | Completion | Fantasy | Design |
| Excitement | Cooperation | Strategy | Power | Story | Discovery |

> Source: [Nick Yee (12/2015) 'Gaming Motivations Group Into 3 High-Level Clusters'](https://quanticfoundry.com/2015/12/21/map-of-gaming-motivations/)

## Emotions & Flow State
Player emotions, an extension of dynamics, are simply how the player feels when playing your game and engaging with the dynamics via the mechanics. Your mechanics should satisfy your players' motivations, but they should just as importantly, if not more importantly, avoid certain feelings.

Generally, in the context of game mechanics, we want the player to reach a flow state while playing that balances the difficulty of the game and their skill with the game. Graphing this identifies two emotions to avoid: boredom and anxiety.

![Flow-State Graph](/images/flow-state-graph-alt.jpg)

> Source: [Learning Loop 'Appropriate Challenges: The user needs appropriate challenges to remain engaged'](https://learningloop.io/plays/psychology/appropriate-challenges)

If the player is not skilled enough with the mechanics to overcome the challenges in the game, they will feel anxious and incapable. If the player is overly skilled to the point of not feeling challenged, they will feel bored and disinterested. These are the emotions you want to purposefully avoid.

> _As a game mechanics designer, your goal is to balance the game’s difficulty with the player’s skill. Doing this requires knowing how quickly a player may progress in skill and pacing the increase in challenge proportionately._

## Noun-Verb Diagrams
Noun-verb diagrams are a simple diagram to visually track how the gameplay systems and objects/entities interact with each other and the players.

> _This can be used to make your **Mechanical Systems Blueprint**._

![noun-verb-diagram-eg](/images/noun-verb-diagram-eg.jpg)

> Source: [@LeenaVanD via Mastodon 'Here's our noun-verb diagram for Dead Static Drive's core gameplay loop'](https://peoplemaking.games/@LeenaVanD/109341406366003091)

## Playable Prototype
A playable prototype is a rudimentary build of your game without all the aesthetic polish of a market-ready game. It consists of the core systems that allow the game to function mechanically so you can test it before investing in said polish.

> _Many game developers will go straight into prototyping an idea before all the details are established. This is good practice for rapidly prototyping a lot of ideas in a short amount of time to find something that sticks. Once a good idea is found, further details can be considered to better tune and target the game for an audience._

Game developers tend to use pre-built game engines to build their games from prototype to final product, the most popular ones being **Godot**, **Unity**, and **Unreal**.

Each engine can more or less do the same thing, but each one is catered to different crowds.
- [**Godot**](https://godotengine.org/) is very popular among independent developers as it is open-source, which means there are no licensing fees to use it. It uses a scripting language called **GDScript** which is based on Python, but it can also be bound to any other language like C# or even Rust! The engine is maintained by the community though primarily funded via the [**Godot Foundation**](https://godot.foundation/).

- [**Unity**](https://unity.com/) has been popular amongst independent developers as well as AAA developers. It uses **C#** which is maintained by **Microsoft**, though the engine itself is maintained by [**Unity Technologies**](https://unity.com/our-company).

- [**Unreal**](https://www.unrealengine.com/) has been a go-to for AAA developers who want high graphical fidelity for their games. It uses **C++** as well as **Blueprints**: a visual scripting tool. Both the engine and visual scripting are maintained by [**Epic Games**](https://www.epicgames.com/site/about).

Each of those engines are perfectly capable for rapid prototyping, and whichever one you pick is up to you and your needs.

> _Regardless of which engine you pick, the principles used in programming and prototyping are largely the same across engines. You could have a hobby project in Godot, another in Unity, and a larger team project in Unreal._
>
> _You don't have to limit yourself!_

---

|**<<<**|**<**|**>**|**>>>**|
|-|-|-|-|
| _[PHASE 0 - Preparation](../0-preparation)_ | _[PHASE 1 - Pre-Production](../1-pre-production/README.md)_ | _[P1-STEP 2 : Interactive Design](2-interactive-design.md)_ | _[PHASE 2 : Production]()_ |