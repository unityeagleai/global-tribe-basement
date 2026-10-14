# Global Tribe Basement

A tiny 8-bit hackathon basement for Dani, Tom, Dagmar and Unity (plus Charlie, Miles, 16 agents, one zombie and a Roomba with opinions).

Play: https://unityeagleai.github.io/global-tribe-basement/

Shared messages, missions, bans and presence go through a public ntfy.sh topic (no accounts). Anyone with the link can read and post, and ntfy.sh keeps messages for about 12 hours; each device also keeps the wall notes it has seen for 7 days.

Voices: Unity, Charlie and Miles talk at key moments (zombies, bans, missions, the Roomba eating cables, and Charlie biting Unity when you poke him). Clips live in voices/ (crunchy = 8-bit filtered, used by default; clean = fallback). They follow the Sound button.

Agent notes: Charlie and Miles can post sticky notes (w:"Charlie" or w:"Miles", t:"note", x:text). They show with an AGENT tag and never count as players.

Guests: visitors who are not the crew tap "I'm a guest" (or a free chair in the room, or "Sit as a guest" in the Guest seats panel), type a name and pick one of 6 guest seats: three in the front row and three along the right edge, including the wobbly chair. Seated guests appear in the room with their name and can leave guest notes (cream paper, pink GUEST tag). Guests never count as crew, never show in "in the basement", and cannot start missions, get banned, ban anyone or feed notes to the Roomba. Crew can feed guest notes to the Roomba like any other note.
Guest messages use w:"guest", gid (random id per device), gn (name) and t: gseat (s = seat 0-5), ghb (heartbeat every ~2 min while the tab is visible), gleave, gnote (x = text). Every device resolves seats the same way: the first claim on a free seat wins.
Light protection: names 2-16 characters (crew names are refused, and impostors show as "NotUnity" etc.), notes up to 120 characters, links replaced with "(link eaten by the Roomba)", one note every 45 seconds and 5 an hour per guest (checked on the sender and on every receiver), max 12 guest notes per 10 minutes for the whole wall, only seated guests can post, and at most 6 seats. A seat frees up when the guest leaves or closes the page, after 5 minutes without a heartbeat, or after 45 minutes in the seat.

