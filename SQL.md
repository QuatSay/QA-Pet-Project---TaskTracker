-- Проверить задачи текущего пользователя
SELECT * FROM tasks WHERE user_id = 1;


-- Проверить задачи со статусом 'Done'
SELECT * FROM tasks WHERE status = 'Done';
