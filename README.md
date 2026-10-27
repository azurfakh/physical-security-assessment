# Physical Security Assessment

A hands-on project from my cybersecurity training on physical security:
protecting buildings, rooms and equipment from unauthorized access, theft,
vandalism and fire. I worked through a fictional organization and had to
decide what to protect first, what to buy, and which measures are worth
the money.

> Note: the result files in this repository are written in Russian.
> This README summarizes them in English.

## Tasks

### 1. Protected Zones and Priorities
Given a building layout, I ranked each zone by priority (A, B, C) and
decided where access control is needed.
- **Server room and warehouse: priority A.** The server room holds the
  critical infrastructure; the warehouse holds valuable assets that must
  be registered and inspected.
- **Zones next to the server room: priority B.** They act as buffer areas
  on the way to the critical room, so I recommended access control there.
- **Outer corner rooms: priority C.** I proposed the corner room with an
  outside wall for the emergency fire exit, because it is farthest from
  critical zones and does not weaken their protection.
- **Files:** `task_1/security_zones.txt`, `task_1/task1.png`

### 2. Server Room Equipment List
Compiled a list of equipment to buy for the server room, using an AI
assistant as a consultant. The full dialogue, with my comments, is in the
`ai_task2_dialogue.txt` file.
- **Files:** `task_2/buying_list.xlsx`, `task_2/ai_task2_dialogue.txt`

### 3. Organizational Measures
For a 50-person organization, I sorted 20 proposed security measures into
effective and unsuitable ones, and justified every decision.
- **Effective (13):** pass system with access levels, escorting visitors,
  no unescorted access to the server room, visitor registration,
  biometric access for the server room, incident response instructions,
  staff training, a person responsible for physical security, and locking
  workstations when leaving (clean-screen policy), among others
- **Unsuitable (7):** measures that belong to other areas, such as USB
  bans and email filters (information security), or that create new
  risks, such as keeping the keys to every room in one box at reception
- **Files:** `task_3/I_4m_the_security.txt`, `task_3/ai_task3_dialogue.txt`

### 4. Security Budget Planning
Chose security measures for a mid-size company (3 floors, warehouse,
server room) with a budget of 2,500,000 rubles, against four threats:
unauthorized access, equipment theft, vandalism and fire.
- **Selected:** access control system, pass system, metal bars on server
  room windows, anti-vandal equipment cases, automatic fire suppression,
  and smoke and temperature sensors
- **Spent:** 2,180,000 rubles, with 320,000 kept as a reserve
- **Rule I applied:** every threat is covered by at least two measures
- **Rejected:** a guard post and an internal audit (1,000,000 rubles per
  year each, too expensive for the budget), and a turnstile and outdoor
  siren (they duplicate functions already covered)
- **Files:** `task_4/answer.txt`, `task_4/measures.xlsx`

## Key Takeaways
- Priorities come first: protect the most critical zones first, and
  protect the approaches to them too
- Two partial measures can together fully cover a threat, and it is
  cheaper to combine them than to buy one expensive solution
- Many measures that sound like security (USB bans, email filters)
  belong to other areas, so scope matters
- A weak measure can create a new risk, for example storing all keys in
  one place

## Disclaimer
All content is for educational purposes. The organization and scenarios
are fictional.
