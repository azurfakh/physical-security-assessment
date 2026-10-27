# Physical Security Assessment

A hands-on project from my cybersecurity training on physical security:
protecting buildings, rooms and equipment from unauthorized access, theft,
vandalism, fire and other physical threats. Working through a fictional
organization, I had to decide what to protect first, what equipment to
buy, which organizational rules to introduce, and how to spend a limited
security budget. The project follows the recommendations of the Russian
standard GOST R ISO/IEC 17799-2005 (the Russian version of ISO 17799).

> Note: the result files in this repository are written in Russian.
> This README summarizes them in English.

**Topics covered:** protected zones and security perimeters, access control
systems, equipment and cabling protection, power supply, organizational
policies (such as clean desk and clean screen), and budget-based risk
treatment.

## Tasks

### 1. Protected Zones and Priorities
Given an office floor plan, I ranked each zone by priority (A highest,
B medium, C lowest), chose the zones that need an access control system,
and decided where the emergency fire exit should go.
- **Server room and warehouse: priority A.** The server room holds the
  critical infrastructure; the warehouse holds valuable assets that must
  be registered and inspected.
- **Zones next to the server room: priority B.** They are buffer areas on
  the way to the critical room, so I recommended access control there too.
- **Outer corner rooms: priority C.** I placed the fire exit in the corner
  room with an outside wall, because it is farthest from critical zones,
  so the exit does not weaken their protection, and it gives the shortest
  evacuation route.
- **Files:** `task_1/security_zones.txt`, `task_1/task1.png`

### 2. Server Room Equipment List
Compiled a list of additional equipment to protect a server room with
5 servers and 1 administrator workstation (cooling already in place).
The list has at least four items, each with a quantity and the protection
measure it implements (access control, fire protection, power supply
protection and so on). I used an AI assistant as a consultant, checked its
suggestions myself, and documented what I accepted and rejected.
- **Files:** `task_2/buying_list.xlsx`, `task_2/ai_task2_dialogue.txt`

### 3. Organizational Measures
For a 50-person organization with a server room, warehouse, offices,
reception and meeting rooms, I sorted 20 proposed measures into effective
and unsuitable ones. The task required at least 10 effective and 3
unsuitable measures; I classified all 20 and justified each decision.
- **Effective (13):** pass system with access levels, escorting visitors,
  no unescorted access to the server room, visitor registration,
  equipment marking and registration, biometric access for the server
  room, incident response instructions, staff training, a person
  responsible for physical security, and locking workstations when
  leaving (clean-screen policy), among others
- **Unsuitable (7):** measures that belong to other areas, such as USB
  bans and email filters (information security), irrelevant ones such as
  daily meetings, or ones that create new risks, such as keeping the keys
  to every room in one box at reception
- **Files:** `task_3/I_4m_the_security.txt`, `task_3/ai_task3_dialogue.txt`

### 4. Security Budget Planning
Chose security measures for a mid-size company (3 floors, warehouse,
server room) with a budget of 2,500,000 rubles, against four threats:
unauthorized access, equipment theft, vandalism and fire. Rule: every
threat needs at least two measures (two partial measures count as one
full one).
- **Selected:** access control system, pass system, metal bars on server
  room windows, anti-vandal equipment cases, automatic fire suppression,
  and smoke and temperature sensors
- **Spent:** 2,180,000 rubles, with 320,000 kept as a reserve
- **Rejected:** a guard post and an internal audit (1,000,000 rubles per
  year each, too expensive for the budget), and a turnstile and outdoor
  siren (they duplicate functions already covered)
- **Files:** `task_4/answer.txt`, `task_4/measures.xlsx`

## Key Takeaways
- Priorities come first: protect the most critical zones first, and
  protect the approaches to them too
- Two partial measures can together fully cover a threat, and combining
  them is often cheaper than one expensive solution
- Many measures that sound like security (USB bans, email filters)
  belong to other areas, so scope matters
- A weak measure can create a new risk, for example storing all keys in
  one place

## Disclaimer
All content is for educational purposes. The organization and scenarios
are fictional.
