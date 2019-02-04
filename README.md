# werewolf

The purpose of building this game (which I do not own) is to basically allow my friends/family to easliy play the werewolf game without having a deck of cards on hand.

It should allow options to set number of **werewolves**, **villagers**, **one doctor** and **one seer**

Leverage [socket.io](https://socket.io/) to handle real-time updates and broadcast events across devices.

Phase 1:
1. users are allowed to create new rooms
2. the room creator is admin
3. users can join waiting rooms via url and are requested to add user name
4. admin can set game options such as # of werewolves, doctors, seer and etc.
5. villagers will auto calculate
6. admin can start the game which will randomly distribute the roles across all users who joined the room.
7. users should be able to tap their cards to show and hide who they are.
8. admim should be able to view each users cards.