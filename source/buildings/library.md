# Library

The Library is the *ONLY* way for you to raise your Citizen's Skills. When a Citizen Spawns, it will spawn with random skills, but the level of the skills also depend on the [happiness](../../source/tutorials/happiness) level of the Town. So if the happiness level is low then the new citizens will spawn with low skill stats. In any case, if your citizen's have low skill stats, then it's time to get your citizens educated! For that purpose we have the Library. After you have crafted the Library block, use your [Building Tool](../../source/tutorials/building_tool) to place the building.

<br>
<p style="text-align:center;"><img src="../../assets/images/Buildings/library_recipe.png" alt="Library Recipe"></p>
<br><br>

You can aasign Citizens to the library from it's GUI, but only 2 citizens can be assigned per Library level. So we have: 

| Building Level | Citizens "Educated" |
| ----- | ----- |
| 1 | 2 |
| 2 | 4 |
| 3 | 6 |
| 4 | 8 |
| 5 | 10 |

<br><br>
- **Note:** The Citizen will be *RANDOMLY* leveling up their skills as long as it's assigned to the Library. Once you are satisfied with the level of skills it has reached, you have to *FIRE* it from the Library so it can be unemployed again and you can now *HIRE* it in any other worker hut, guard, etc. Awesome, right?

<br><br>

## Hut GUI

When accessing the Library's Hut block (right clicking on it) you will see a GUI with different options:

<div class="row">
  <div class="col-sm-12 col-md">
    <img src="../../assets/images/gui/librarygui.png" class="img-fluid mx-auto" alt="Library GUI">
  </div>
  <div class="col-sm-12 col-md">
    <br>
    <br>
    <p> This is the GUI for the Library's Hut. It shows the build "level" of the Hut. And the buttons:</p>
    <br>
    <br>
    <ul>
      {% for item in site.data.gui.global %}
        <li><strong>{{ item.button }}:</strong> {{ item.content }}</li>
      {% endfor %}
    </ul>
  </div>
</div>

**Note:** The unemployed citizens will be the only ones available to *HIRE* in the Library. You will only be able to see available citizens to hire if there is room in the Library (according to it's level). So for example, if you have a Library level 1, you can only hire 2 citizens. If it already has 2 citizens assigned, it will only show you those two citizens currently assigned, with the "fire" button and will not list anymore to hire, until there is space availabe.
