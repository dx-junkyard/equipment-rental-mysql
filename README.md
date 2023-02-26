# equipment-rental-mysql

## FacilityReservations
### 体育館や運動場など施設の予約管理を行うテーブル
### This table manage reservations of gymnasiums and the athletic ground.
- reservation_id / 予約ID(PK)
- facility_id / facility_id (Facilityes.facility_id)
- borrower_id / user id (Users.user_id)
- event_id / Event


## EquipmentReservations
### ボールなどの備品の予約管理を行うテーブル
### This table manage reservations of equipment like a ball , etc.
