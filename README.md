# --- имя: Setup .NET Core SDK
 пользы: actions/setup-dotnet@v1.5.0
 с:
 # Версия SDK для использования. Примеры: 2.2.104, 3.1, 3.1.икс
 dotnet-версия: # опционный
 # Дополнительный источник пакета, для которого нужно настроить аутентификацию. Проконсультируйтесь с любым существующим NuGet.сконфигурируйте в корне РЕПО и предоставьте временный NuGet.конфигурация с использованием переменной среды NUGET_AUTH_TOKEN в качестве ClearTextPassword
 источник-url: # необязательно
 # Необязательный владелец для использования пакетов из реестра пакетов GitHub организаций / пользователей, отличных от текущего владельца репозитория. Используется только в том случае, если GPR URL также указан в source-url
 владелец: # необязательно
 # Необязательный NuGet.расположение конфигурации, если ваш NuGet.конфигурация не находится в корневом каталоге репозитория.
 конфигурационный файл: # необязательно
 # Возражавшую. Вместо этого используйте dotnet-версию. Не будет поддерживаться после 1 октября 2019 года
 версия: # опционный---
