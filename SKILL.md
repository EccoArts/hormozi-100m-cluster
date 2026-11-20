---
name: hormozi-100m-cluster
version: 1.0.0
description: >-
  Мастер-кластер бизнес-навыков Алекса Хормози (5 навыков субагента hormozi-business-auditor):
  инженерия неотразимых предложений ($100M Offers), машина лидогенерации ($100M Leads: Core Four & Lead Getters),
  скрипт экспертных продаж CLOSER и отработка возражений, денежные модели и прайсинг ($100M Money Models / CFA),
  снижение оттока (Churn Playbook Acquisition.com) и 100-балльный чеклист аудита бизнеса.
---

# Мастер-кластер `hormozi-100m-cluster` (Субагент `hormozi-business-auditor`)

Полный модульный кластер из **5 прикладных навыков** по методологии Алекса Хормози (`Acquisition.com`, трилогия `$100M Offers`, `$100M Leads`, `$100M Money Models`, фреймворк продаж `CLOSER` и плейбуки масштабирования `$0 -> $100M`).

Предназначен для проектирования, стресс-тестирования и пересборки B2B/B2C-продуктов, коммерческих предложений, автоворонок, скриптов Zoom-продаж и юнит-экономики с главной целью — обеспечить **самоокупаемое привлечение клиентов за первые 30 дней (`Client-Financed Acquisition — CFA`)** и максимизировать пожизненную прибыль (`LTV`) при минимальном оттоке (`Churn`).

---

## Состав кластера и маршрутизация по 5 навыкам:

| № | Навык (`Skill ID`) | Зона ответственности и ключевые инструменты | Относительный путь к инструкции |
| :-: | :--- | :--- | :--- |
| **1** | **[hormozi-100m-offers-architect](hormozi-100m-offers-architect/SKILL.md)** | **`$100M Offers` (Инженерия Grand Slam Offer):** скоринг рынка «Голодная толпа» по 4 индикаторам (`Massive Pain`, `Purchasing Power`, `Easy to Target`, `Growing Market`), Уравнение ценности Хормози со сведением знаменателя (`Time Delay × Effort`) к нулю, 5-шаговый конвейер `Trim & Stack`, архитектура бонусов без скидок, честный дефицит (`Scarcity`), срочность (`Urgency`), 4 типа гарантий (`Risk Reversal`) и формула нейминга `M-A-G-I-C`. | `skills/hormozi-100m-cluster/hormozi-100m-offers-architect/SKILL.md` |
| **2** | **[hormozi-100m-leads-machine](hormozi-100m-leads-machine/SKILL.md)** | **`$100M Leads` (Машина лидогенерации Core Four & Lead Getters):** 7 шагов создания убойного Лид-магнита в 3 форматах (`Software/Tool`, `Information`, `Service/Trial with skin in the game`), матрица `Core Four` (Тёплые касания `A-C-A`, Контент `Hook -> Retain -> Reward`, Холодные касания и рассылки, Платная реклама `Callout -> Value -> CTA`), закон «Правило 100» (`Rule of 100`) и 4 рычага чужих рук (`Lead Getters`). | `skills/hormozi-100m-cluster/hormozi-100m-leads-machine/SKILL.md` |
| **3** | **[hormozi-closer-sales-system](hormozi-closer-sales-system/SKILL.md)** | **Система продаж `CLOSER` и закрытие возражений:** полный протокол экспертной встречи `C-L-O-S-E-R` (`Clarify -> Label -> Overview Past Pain -> Sell the Vacation, Not the Plane Flight -> Explain Away Concerns -> Reinforce`), продажа «отпуска на Мауи в 3 тезисах» вместо технических деталей, петля снятия 3 истинных барьеров (Время, Деньги, Партнёр/ЛПР) и 5-минутный онбординг против `Buyer's Remorse`. | `skills/hormozi-100m-cluster/hormozi-closer-sales-system/SKILL.md` |
| **4** | **[hormozi-money-models-and-pricing](hormozi-money-models-and-pricing/SKILL.md)** | **`$100M Money Models` & Прайсинг:** закон `Client-Financed Acquisition (CFA)` — кэш за первые 30 дней $\ge 2 \times (\text{CAC} + \text{COGS})$, лестница монетизации (`Attraction Offer` $\to$ 4 вида `Upsell`: `Classic`, `Menu`, `Anchor`, `Rollover` $\to$ `Downsell` без скидок на тот же объём $\to$ `Continuity`) и 10 золотых правил прайсинга Хормози (`Waived Setup Fee`, 28-дневный цикл биллинга, привязка карты на старте). | `skills/hormozi-100m-cluster/hormozi-money-models-and-pricing/SKILL.md` |
| **5** | **[hormozi-retention-and-scaling-audit](hormozi-retention-and-scaling-audit/SKILL.md)** | **`Acquisition.com` Удержание (`Churn Playbook`) и Масштабирование (`$0 -> $100M`):** 9 шагов снижения оттока (`Activation Point`, персональный онбординг, `Quick Win` за 48 часов, регулярная оцифровка ROI, Exit-интервью), этапы роста бизнеса и **100-балльный чеклист аудита бизнеса (`Hormozi 100-Point Business Audit Scorecard`)** по 5 осям (по 20 баллов на каждую ось). | `skills/hormozi-100m-cluster/hormozi-retention-and-scaling-audit/SKILL.md` |

---

## Порядок работы субагента `hormozi-business-auditor`:

1. При полном бизнес-аудите проекта субагент последовательно вычитывает все 5 навыков кластера и оценивает бизнес по **100-балльной матрице (`Hormozi 100-Point Scorecard`)**.
2. При точечной задаче (переупаковка оффера, починка кассового разрыва `CFA`, написание скрипта Zoom-продажи `CLOSER` или снижение оттока в подписке) субагент обращается к профильному навыку кластера и выдаёт готовые к внедрению артефакты с расчётами в деньгах и дословными речевыми формулировками.
