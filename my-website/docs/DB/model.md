---
title: Модель данных
sidebar_position: 1
---

# Модель данных

import Drawio from '@theme/Drawio'
import diagram from '!!raw-loader!./model.drawio';

<Drawio content={diagram} editable={false} />


## Службы

| Название   | Тип          | Описание             |
| ---------- | ------------ | -------------------- |
| service_id | UUID PK      | Идентификатор службы |
| name       | varchar(255) | Наименование службы  |
| district   | enum         | Район службы         |
