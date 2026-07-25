24th July, 2026
Learnings:
I learned the basics of HTML, a bit of DOM, why the structure exists, metadata, why we need to maintain a structure and follow the structure and that DOM is nothing but the HTML document tree.

Challenges: 
I think it took me a while to get the metadata part and the supabase why supase is having 2 things one is the database and one is the storage

Learnings: 
Software Engineering Insights: Components
AS i created a Navbar in my webpage, it is my first UI component. The navbar is a component because it has one responsibility.
It will appear on multple pages.
It can evolve independently. Later, when we move on to React framework, the entire navbar would become Navbar.jsx but the concept stays the same. Frameworks dont replace good architecture rather they buiild on it. 

Logo Recommendation: professional blogs use s 48px x 48px logo or 64x64 and SVG would be ideal, if not, PNG with transparent background also works 
Also its better to keep the website name different than that from the youtube channel name and instgram. This actually creates a separate branding entity Keychronicle by Acheso Is Typing

New Terminologies for Git for commit
| Prefix      | Meaning                                |
| ----------- | -------------------------------------- |
| `feat:`     | New feature                            |
| `fix:`      | Bug fix                                |
| `style:`    | CSS / formatting                       |
| `refactor:` | Improve code without changing behavior |
| `docs:`     | Documentation                          |
| `test:`     | Unit or integration tests              |
| `chore:`    | Project maintenance and setup          |


25th July, 2026
Analogy for CSS box model
Wheneve i am unsure about the margin and padding in css, i will imagine a keyboard carrying case
Margin
┌──────────────────────────────┐
│                              │
│   Border                     │
│   ┌──────────────────────┐   │
│   │      Padding         │   │
│   │  ┌──────────────┐    │   │
│   │  │  Keyboard    │    │   │
│   │  └──────────────┘    │   │
│   └──────────────────────┘   │
│                              │
└──────────────────────────────┘
where,
keyboard = content 
foam around the keyboard = padding
carrying case = border
empty shelf space around the case = margin

Why Use Gap on Flex Items?
Why

gap:24px;

instead of

li{
margin-right:24px;
}

Imagine we have

Home   Reviews   About   Contact

With margins:

Home----Reviews----About----Contact----

Notice something?

The last item still has a right margin.

That means unnecessary space.

With

gap

the browser understands

"Create spacing between flex items."

So it becomes

Home----Reviews----About----Contact

No extra space after Contact.

Another huge advantage

Suppose tomorrow we add

Gallery

We don't touch CSS.

Gap automatically becomes

Home----Reviews----Gallery----About----Contact

This is why modern CSS almost always uses gap instead of margins for spacing flex or grid items.


