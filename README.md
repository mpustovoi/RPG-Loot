<details>
<summary>RU</summary>

# RPG-добыча

Набор с RPG-добычей для ванильной игры.

Этот набор добавляет RPG-добычу, которую можно получить, убивая некоторых мобов и найдя в некоторых ванильных структурах.

Он вдохновлён [**RPG Loot, Mobs & Dungeons Data Pack**](https://www.planetminecraft.com/data-pack/rpg-loot-data-pack/) от [michael9r9r](https://www.planetminecraft.com/member/michael9r9r/) и содержит некоторые названия предметов оттуда, но не содержит пользовательских мобов и подземелья.

### Детали

Вот небольшой список мобов, с которых могут выпадать RPG-предметы:
| Моб           | Кол-во | Разнообразие                    |
|---------------|--------|---------------------------------|
| Разоритель    | 1-2    | Необычные, редкие и эпические   |
| Кролик-убийца | 1-2    | Редкие, эпические и легендарные |
| Гигант        | 1-3    | Редкие, эпические и легендарные |
| Древний страж | 1-4    | Необычные, редкие и эпические   |
| Хранитель     | 2-4    | Редкие, эпические и легендарные |
| Иссушитель    | 6-12   | Редкие, эпические и легендарные |
| Эндер-дракон  | 8-16   | Редкие, эпические и легендарные |


В будущем этот список быть расширен некоторыми мобами из модов.

Примерное распределение вероятностей выпадения RPG-предметов:
| Редкость    | Шанс   |
|-------------|--------|
| Необычный   | ~63.3% | 
| Редкий      | ~25.3% |
| Эпический   | ~9.5%  |
| Легендарный | ~1.9%  |

Количество и редкость RPG-предметов, которые можно найти в ванильных структурах, в общем зависит от редкости ванильной добычи, которую в них можно найти.
Структуры из модов, использующие (а не переопределяющие) эти таблицы добычи, также будут иметь RPG-предметы в своих сундуках.

Возможно, в отдалённом будущем для некоторых предметов будут добавлены пользовательские текстуры.

<details>
<summary>Команды для получения RPG-предметов</summary>

| Команда                                   | Результат выполнения  |
| ------------------------------------------|-----------------------|
| `/function rpglott:give/random_item`      | 1 случайный предмет   |
| `/function rpglott:give/random_potion`    | 1 случайное зелье     |
| `/function rpglott:give/uncommon_item`    | 1 необычный предмет   |
| `/function rpglott:give/uncommon_potion`  | 1 необычное зелье     |
| `/function rpglott:give/rare_item`        | 1 редкий предмет      |
| `/function rpglott:give/rare_potion`      | 1 редкое зелье        |
| `/function rpglott:give/epic_item`        | 1 эпический предмет   |
| `/function rpglott:give/epic_potion`      | 1 эпическое зелье     |
| `/function rpglott:give/legendary_item`   | 1 легендарный предмет |
| `/function rpglott:give/legendary_potion` | 1 легендарное зелье   |

</details>

### ⚠ Примечания
- Чтобы получать предметы из гиганта, необходимо установить мод, позволяющий ему появляться в мире, например, [**Giant Spawn**](https://modrinth.com/mod/giant-spawn).
- Чтобы получать предметы из кролика-убийцы, необходимо установить мод, позволяющий ему появляться в мире, например, [**Breedable Killer Rabbit**](https://modrinth.com/mod/breedable-killer-rabbit). (Однако в некоторых сценариях таблица добычи все ещё может не работать.)
- Также рекомендуется установить датапак [**True Ending: Ender Dragon Overhaul**](https://modrinth.com/datapack/true-ending) и мод [**Bedrock Edition Style Wither**](https://modrinth.com/mod/be-style-wither) для большей сложности.

</details>

# RPG-Loot

RPG Loot pack for vanilla game.

This pack adds RPG loot, which can be obtained by killing some mobs and found in some vanilla structures.

It's is inspired by [**RPG Loot, Mobs & Dungeons Data Pack**](https://www.planetminecraft.com/data-pack/rpg-loot-data-pack/) by [michael9r9r](https://www.planetminecraft.com/member/michael9r9r/) and contains some item names from there, but doesn't contain custom mobs and dungeons.

## Details

Here is a small list of mobs that can drop RPG items:
| Mob            | Items | Variety                |
|----------------|-------| ---------------------- |
| Ravager        | 1-2   | Uncommon, Rare & Epic  |
| Killer Rabbit  | 1-2   | Rare, Epic & Legendary |
| Giant          | 1-3   | Uncommon, Rare & Epic  |
| Elder Guardian | 1-4   | Uncommon, Rare & Epic  |
| Warden         | 2-4   | Rare, Epic & Legendary |
| Wither         | 6-12  | Rare, Epic & Legendary |
| Ender Dragon   | 8-16  | Rare, Epic & Legendary |

In the future, this list will be expanded with some modded mobs.

Approximate probability distribution of RPG item drops:
| Rarity    | Chance |
|-----------|--------|
| Uncommon  | ~63.3% | 
| Rare      | ~25.3% |
| Epic      | ~9.5%  |
| Legendary | ~1.9%  |

The number and rarity of RPG items that can be found in vanilla structures generally depends on the rarity of the vanilla loot that can be found in them.
Modded structures that use (not override) these loot tables will also receive RPG items in their chests.

Maybe in the distant future, custom textures will be added for some items.

<details>
<summary>Commands for obtaining RPG items</summary>

| Command                                   | Execution result   |
| ------------------------------------------|--------------------|
| `/function rpglott:give/random_item`      | 1 random item      |
| `/function rpglott:give/random_potion`    | 1 random potion    |
| `/function rpglott:give/uncommon_item`    | 1 uncommon item    |
| `/function rpglott:give/uncommon_potion`  | 1 uncommon potion  |
| `/function rpglott:give/rare_item`        | 1 rare item        |
| `/function rpglott:give/rare_potion`      | 1 rare potion      |
| `/function rpglott:give/epic_item`        | 1 epic item        |
| `/function rpglott:give/epic_potion`      | 1 epic potion      |
| `/function rpglott:give/legendary_item`   | 1 legendary item   |
| `/function rpglott:give/legendary_potion` | 1 legendary potion |

</details>

### ⚠ Notes
- To receive the drops of the Giant, you need to install a mod that allows him to spawn in the world, such as the [**Giant Spawn**](https://modrinth.com/mod/giant-spawn) mod.
- To receive the drops of the Killer Rabbit, you need to install a mod that allows him to spawn in the world, such as the [**Breedable Killer Rabbit**](https://modrinth.com/mod/breedable-killer-rabbit) mod. (However, the loot table may still not work in some scenarios.)
- It is also recommended to install the [**True Ending: Ender Dragon Overhaul**](https://modrinth.com/datapack/true-ending) data pack, as well as [**Bedrock Edition Style Wither**](https://modrinth.com/mod/be-style-wither) mod for better challenge.