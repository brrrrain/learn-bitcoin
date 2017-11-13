## Создадим виртуальное окружение
virtualenv -p /usr/bin/python3 .env

## Активируем виртуальное окружение
source .env/bin/activate

## Установим зависимости
pip install -r requirements.txt

## Запустим Jupyter notebook
./up.sh
