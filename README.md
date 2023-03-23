# Домашнее задание

## Задание №1
![image](https://user-images.githubusercontent.com/102313283/226348117-5a77efa2-eadd-4d70-8ef4-5bb0e86a5f12.png)

Ответ на доп вопрос: Без использования pull request нужно выполнить следующие команды: обновить локальный репозиторий - `git pull` (Эта же команда в другой вариации -`git fetch & git merge`), внести изменения в проект и выполнить `git push`.
https://github.com/Keldwar/HomeWork1/pulls

## Задание №2
![image](https://user-images.githubusercontent.com/102313283/226351206-9f404488-7977-467b-8b68-7bc7da15a63d.png)

 Ответ на доп. вопрос: не удалось запушить изменения, т.к. после `rebase` состояния локального и удаленного рекпозитория отличаются (хэши коммитов различаются).
 
 Решение: использовать `git push --force` (быть аккуратнее, т.к. при использовании данного флага отключается проверка коммитов и выполняется перезапись истории).
 
 ## Задание 3
 Создали 3 коммита
 ![image](https://user-images.githubusercontent.com/102313283/226356760-01020163-984c-4d2a-8fac-b3735be73195.png)
 ![image](https://user-images.githubusercontent.com/102313283/226356985-51d9c07b-1250-4077-a366-6a990b553345.png)
