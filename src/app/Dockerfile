WORKDIR /app

# Копируем из корня (так как context: .)
COPY pyproject.toml poetry.lock* ./

# Копируем исходники
COPY . .