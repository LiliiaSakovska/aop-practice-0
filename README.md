Саковська Лілія, група f3,211(онлайн)
GitHub: https://github.com/LiliiaSakovska
LeetCode: https://leetcode.com/u/liliiasakovska/
HackerRank: https://www.hackerrank.com/profile/liliasakovska91
<img width="1280" height="673" alt="image" src="https://github.com/user-attachments/assets/5703eedf-a177-4fc7-b6f0-6e46367ea637" />
<img width="1280" height="195" alt="image" src="https://github.com/user-attachments/assets/766407d1-05a1-476a-8cd5-4809c252938a" />
<img width="1366" height="768" alt="Знімок екрана (7)" src="https://github.com/user-attachments/assets/2295e159-ad44-4867-b9ee-283329006431" />
<img width="589" height="1280" alt="image" src="https://github.com/user-attachments/assets/ae9c1ea1-dc4b-48d0-8278-50f2c43a9171" />
Доступ до Claude Code не оформлювався
Опис проблем та способів їх усунення
Під час виконання команди ssh -T git@github.com відбувався збій формування шляхів до папки .ssh і файлу known_hostsчерез наявність кирилиці.
Спосіб усунення: Для обходу збереження хоста та точної вказівки файлу ключа використано команду з прапорцями: ssh -o StrictHostKeyChecking=no -o UserKnownHostsFile=/dev/null -i ~/.ssh/id_ed25519 -T git@github.com
