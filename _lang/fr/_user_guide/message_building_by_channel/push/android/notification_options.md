---
nav_title: "Options de notification"
article_title: Options de notification Android
page_order: 2
page_type: reference
description: "Le présent article de référence couvre plusieurs options de notification Android et comment les utiliser au mieux dans les campagnes Braze."

platform: Android
channel:
  - Notification push

---

# Options de notification Android

> Si vous souhaitez catégoriser vos messages et les regrouper dans la zone de notification de votre utilisateur, vous pouvez utiliser la fonction de canaux de notification d’Android via Braze.

Créez votre campagne de notification push Android, puis regardez en haut de l’onglet **Compose** (Composer) pour trouver la liste déroulante **Notification Channel** (Canal de notification).

![][28]{: style="max-width:60%;" }

Sélectionnez votre canal de notification dans la liste déroulante. Vous devez également sélectionner un canal de secours en cas de dysfonctionnement de votre paramètre de canal de notification.

Si vous n’avez aucun [Notification Channel]({{site.baseurl}}/user_guide/message_building_by_channel/push/android/notification_channels/) (Canal de notification) listé, vous pouvez en ajouter un à l’aide de l’ID de canal de notification. Contactez vos développeurs pour trouver quels sont vos ID de canal de notification ou pour en créer de nouveaux si besoin. 

Pour ajouter un ID de notification à votre canal de notification, cliquez sur **Manage Notification Channel** (Gérer le canal de notification) dans la liste déroulante **Notification Channel** (Canal de notification) et remplissez les champs requis. Les canaux de notification doivent être définis sur l’application avant de pouvoir être utilisés sur la plateforme Braze.

![][29]{: style="max-width:80%;" }


[28]: {% image_buster /assets/img_archive/notification_channel_dropdown.png %}
[29]: {% image_buster /assets/img_archive/notification_channels.png %}
