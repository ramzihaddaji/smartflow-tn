# Modèle de données

## Leads
lead_id, full_name, phone, email (opt.), training_id, source (opt.), status, created_at, next_follow_up (opt.), notes (opt.)

## Trainings
training_id, name, description, duration, price, active

## FollowUps
follow_up_id, lead_id, date, action (Appel/Message), result, completed

## StatusHistory
history_id, lead_id, old_status, new_status, changed_at

## Settings
Nom du centre, e-mail du responsable, téléphone, message WhatsApp, notifications.

SaaS futur : ajouter tenant_id.
