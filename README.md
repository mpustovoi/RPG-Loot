<details>
<summary>RU</summary>

# RPG-Добыча

Набор с RPG-добычей для ванильной игры.

Этот набор добавляет RPG-добычу, которую можно получить, убивая некоторых мобов и найдя в некоторых ванильных структурах.

Он вдохновлён [**RPG Loot, Mobs & Dungeons Data Pack**](https://www.planetminecraft.com/data-pack/rpg-loot-data-pack/) от michael9r9r и содержит некоторые названия предметов оттуда, но не содержит пользовательских мобов и подземелья.

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

Каждый из них также содержит несколько уникальных предметов добычи.


В будущем этот список может быть расширен некоторыми мобами из модов путём добавления небольших наборов-аддонов.

Общее примерное распределение вероятностей выпадения RPG-предметов:
| Редкость    | Шанс   |
|-------------|--------|
| Необычный   | ~63.3% | 
| Редкий      | ~25.3% |
| Эпический   | ~9.5%  |
| Легендарный | ~1.9%  |

Легендарные предметы являются неразрушаемыми.

Количество и редкость RPG-предметов, которые можно найти в ванильных структурах, в общем зависит от редкости ванильной добычи, которую в них можно найти.
Структуры из модов, использующие (а не переопределяющие) эти таблицы добычи, также будут иметь RPG-предметы в своих сундуках.

Возможно, в отдалённом будущем для некоторых предметов будут добавлены пользовательские текстуры.

<details>
<summary>Команды для получения RPG-предметов</summary>

| Команда                                   | Результат             |
| ------------------------------------------|-----------------------|
| `/function rpgloot:give/random_item`      | 1 случайный предмет   |
| `/function rpgloot:give/random_potion`    | 1 случайное зелье     |
| `/function rpgloot:give/uncommon_item`    | 1 необычный предмет   |
| `/function rpgloot:give/uncommon_potion`  | 1 необычное зелье     |
| `/function rpgloot:give/rare_item`        | 1 редкий предмет      |
| `/function rpgloot:give/rare_potion`      | 1 редкое зелье        |
| `/function rpgloot:give/epic_item`        | 1 эпический предмет   |
| `/function rpgloot:give/epic_potion`      | 1 эпическое зелье     |
| `/function rpgloot:give/legendary_item`   | 1 легендарный предмет |
| `/function rpgloot:give/legendary_potion` | 1 легендарное зелье   |

С помощью этих команд нельзя получить уникальные для мобов из первой таблицы предметы добычи.

</details>

### ⚠ Примечания
- Чтобы получать предметы из гиганта, необходимо установить мод, позволяющий ему появляться в мире, например, [**Giant Spawn**](https://modrinth.com/mod/giant-spawn).
- Чтобы получать предметы из кролика-убийцы, необходимо установить мод, позволяющий ему появляться в мире, например, [**Breedable Killer Rabbit**](https://modrinth.com/mod/breedable-killer-rabbit). (В некоторых сценариях с модами таблица добычи может не работать.)
- Также рекомендуется установить датапак [**True Ending: Ender Dragon Overhaul**](https://modrinth.com/datapack/true-ending) и мод [**Bedrock Edition Style Wither**](https://modrinth.com/mod/be-style-wither) для большей сложности.

</details>

# RPG-Loot

RPG Loot pack for vanilla game.

This pack adds RPG loot, which can be obtained by killing some mobs and found in some vanilla structures.

It's is inspired by [**RPG Loot, Mobs & Dungeons Data Pack**](https://www.planetminecraft.com/data-pack/rpg-loot-data-pack/) by michael9r9r and contains some item names from there, but doesn't contain custom mobs and dungeons.

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

Each of them also have several unique loot items.

In the future, this list may be expanded with some modded mobs with by adding small add-ons.

General approximate RPG item drops probability distribution:
| Rarity    | Chance |
|-----------|--------|
| Uncommon  | ~63.3% | 
| Rare      | ~25.3% |
| Epic      | ~9.5%  |
| Legendary | ~1.9%  |

Legendary items are unbreakable.

The number and rarity of RPG items that can be found in vanilla structures generally depends on the rarity of the vanilla loot that can be found in them.
Modded structures that use (not override) these loot tables will also receive RPG items in their chests.

Maybe in the distant future, custom textures will be added for some items.

<details>
<summary>Commands for obtaining RPG items</summary>

| Command                                   | Output             |
| ------------------------------------------|--------------------|
| `/function rpgloot:give/random_item`      | 1 random item      |
| `/function rpgloot:give/random_potion`    | 1 random potion    |
| `/function rpgloot:give/uncommon_item`    | 1 uncommon item    |
| `/function rpgloot:give/uncommon_potion`  | 1 uncommon potion  |
| `/function rpgloot:give/rare_item`        | 1 rare item        |
| `/function rpgloot:give/rare_potion`      | 1 rare potion      |
| `/function rpgloot:give/epic_item`        | 1 epic item        |
| `/function rpgloot:give/epic_potion`      | 1 epic potion      |
| `/function rpgloot:give/legendary_item`   | 1 legendary item   |
| `/function rpgloot:give/legendary_potion` | 1 legendary potion |

Using these commands, you can't get loot items unique to mobs from the first table.

</details>

### ⚠ Notes
- To receive the drops of the Giant, you need to install a mod that allows him to spawn in the world, such as the [**Giant Spawn**](https://modrinth.com/mod/giant-spawn) mod.
- To receive the drops of the Killer Rabbit, you need to install a mod that allows him to spawn in the world, such as the [**Breedable Killer Rabbit**](https://modrinth.com/mod/breedable-killer-rabbit) mod. (The loot table may not work in some modded scenarios.)
- It's also recommended to install the [**True Ending: Ender Dragon Overhaul**](https://modrinth.com/datapack/true-ending) data pack, as well as [**Bedrock Edition Style Wither**](https://modrinth.com/mod/be-style-wither) mod for better challenge.