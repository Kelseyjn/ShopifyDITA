## Rabatt für kostenlosen Versand erstellen

Wenn Sie kostenlosen Versand anbieten möchten, können Sie einen Rabatt für kostenlosen Versand erstellen.

Rabatte für kostenlosen Versand gelten nie automatisch für eine Bestellung. Ihre Kunden müssen den Code beim Checkout eingeben, um den Rabatt zu erhalten. Um Ihren Kunden automatisch den kostenlosen Versand basierend auf dem Bestellwert anzubieten, müssen Sie einen [Tarif für kostenlosen Versand festlegen](/manual/shipping/rates-and-methods/examples/#free-shipping-over-a-set-dollar-amount).

> Hinweis: Richten Sie in Ihrem Shopify-Adminbereich auf einen [Tarif für kostenlosen Versand](/manual/shipping/rates-and-methods/examples/#free-shipping-over-a-set-dollar-amount) auf der Seite [**Versand**](//www.shopify.com/admin/settings/shipping) ein. Er wird auf alle Bestellungen angewendet, die die von Ihnen festgelegten Bedingungen für den kostenlosen Versand erfüllen.

{{ 'xh4DEZVkNuA' | youtube }}

{% include link-to-more-videos.md %}

#### Schritte:

{% sections "Desktop, iPhone, Android" %}

{% comment %} Desktop-Abschnitt {% endcomment %}

{% include admin_sidebar/discounts.md %}

1. Klicken Sie auf der Seite **Rabatte** auf **Rabatt erstellen**.

2. Geben Sie im Abschnitt **Rabattcode** einen Namen für den neuen Rabattcode ein (z. B. `freeshipping4smallorders`). Um einen zufälligen Rabattcode zu generieren, klicken Sie auf **Code generieren**.

3. Wählen Sie im Bereich **Optionen** die Rabattart **Kostenloser Versand**.

4. Lassen Sie im Bereich **Länder** die Option **Alle Länder** ausgewählt oder wählen Sie die Länder aus, für die der Rabatt gelten soll.

    Wenn Sie den kostenlosen Versand für Versandkosten ab einem bestimmten Betrag ausschließen möchten, aktivieren Sie die Option **Versandkosten über einen bestimmten Betrag ausschließen** und geben Sie den Betrag in das Feld ein. Dieser Rabatt gilt nur für die Versandkosten und steht nicht im Zusammenhang mit der Bestellsumme.

5. Wählen Sie im Abschnitt **Kundenberechtigung** aus, für wen dieser Rabatt gelten soll: **Alle**, **Bestimmte Kundengruppen** oder **Bestimmte Kunden**.

    Verwenden Sie das Suchfeld, um die Einzelpersonen oder Gruppen auszuwählen, die den Rabatt erhalten sollen. Kundenlisten geben die E-Mail-Adresse an, mit denen sie sich bei Ihrem Shop registriert haben. Wenn keine E-Mail-Adresse angegeben wurde, wird in der Liste die Telefonnummer des Kunden angezeigt.

    Um einen einzelnen Kunden oder eine Kundengruppe von der Berechtigung für einen Rabatt auszuschließen, klicken Sie auf das **X** neben dem Namen des Kunden oder der Gruppe.

    Weitere Informationen zum Erstellen von Kundengruppen finden Sie unter [_Kunden verwalten_](/manual/customers/manage-customers#create-customer-groups).

6. Die Rabattnutzung ist standardmäßig unbegrenzt. Wenn Sie die Rabattnutzung einschränken möchten, aktivieren Sie eine der Optionen im Abschnitt **Nutzungsbeschränkungen**:

    - Mit **Beschränken, wie oft dieser Rabattcode insgesamt verwendet werden kann** können Sie festlegen, wie oft ein Rabatt insgesamt verwendet werden kann. Wenn Sie beispielsweise ein Limit von 200 festlegen, wird der Rabattcode 200 Mal für Ihren Kundenstamm verwendet. Wenn Sie diese Einstellung wählen, können Kunden den Rabatt mehrmals verwenden.
    - **Auf eine Benutzung pro Kunde beschränken** verfolgt die E-Mails des Kunden, um den Rabatt auf eine Benutzung pro Kunde zu beschränken.

7. Verwenden Sie den Kalender im Abschnitt **Aktive Daten**, um das Startdatum für den Rabatt festzulegen. Wenn Sie ein Enddatum für den Rabatt festlegen möchten, klicken Sie auf **Enddatum festlegen** und verwenden Sie den Kalender, um festzulegen, wann der Rabatt endet:

    ![Rabattdaten](/manual/discounts/discount-active-dates.png)

    Wenn Sie kein Enddatum für Ihren Rabatt auswählen, hat er kein Ablaufdatum. Wenn der Rabatt nur für einen Tag gültig sein soll, wählen Sie den gleichen Kalendertag als Startdatum und Enddatum aus.

> Hinweis: Der Zeitpunkt, zu dem der Rabatt beginnt und endet, hängt von der [Zeitzone ab, die Sie im Shopify-Adminbereich ausgewählt haben](/manual/intro-to-shopify/initial-setup/setup-business-settings/#set-or-change-your-store-timezone). Wenn beispielsweise die Zeitzone Ihres Shops Eastern Standard Time ist und Sie als Startdatum den 26. November auswählen, beginnt Ihr Rabatt am 26. November um 12 Uhr EST.

8. Wenn Sie fertig sind, klicken Sie auf **Rabatt speichern**.

Der neue Rabatt wird jetzt auf der Seite [**Rabatte**](//www.shopify.com/admin/discounts) im Shopify-Adminbereich angezeigt. Um diesen Rabatt zu verteilen, können Sie den Code per E-Mail an Ihre Kunden senden oder in Ihrem Online-Shop anzeigen.

----

{% comment %} iOS-Abschnitt {% endcomment %}

1. Gehen Sie in der [Shopify App](https://www.shopify.com/install/detect) auf **Shop** > **Rabatte**.

2. Tippen Sie auf der Seite **Rabatte** auf die Schaltfläche `+`.

3. Geben Sie im Abschnitt **Rabattcode** einen Namen für den neuen Rabattcode ein (z. B. `freeshipping4smallorders`). Um einen zufälligen Rabattcode zu generieren, klicken Sie auf **Code generieren**:

    ![Rabattcodename für kostenlosen Versand – iPhone](/manual/discounts/discount-name-shipping-iphone.png)

> Hinweis: Vermeiden Sie die Verwendung von Sonderzeichen in Rabattnamen, damit Ihre Rabattnamen korrekt zur Checkout-URL Ihres Shops hinzugefügt werden.

4. Tippen Sie auf **Rabattart** und wählen Sie **Kostenloser Versand**.

5. Wenn Sie eine Mindestanforderung für den Rabatt festlegen möchten, tippen Sie auf **Mindestanforderungen** und wählen Sie eine Anforderung aus:

    - **Mindestabnahmebetrag** erfordert, dass Kunden einen Mindestbetrag ausgeben, um sich für den Rabatt zu qualifizieren.
    - **Mindeststückzahl** erfordert, dass Kunden eine Mindestanzahl von Produkten bestellen, um sich für den Rabatt zu qualifizieren.

> Hinweis: Wenn der Rabatt für ein bestimmtes Produkt oder eine bestimmte Kategorie gilt, tragen nur diese Artikel zu den Mindestkauf- oder Mengenbeträgen bei.

6. Tippen Sie auf **Länder** und wählen Sie die Länder aus, für die dieser Rabatt gelten soll: **Alle Länder** oder **Bestimmte Länder**.

    Um den Rabatt auf bestimmte Länder zu beschränken, wählen Sie **Bestimmte Länder** aus und tippen Sie auf **Hinzufügen**, um die Länderauswahl zu öffnen. Wählen Sie die Länder aus, für die Sie den Rabatt verfügbar machen möchten, und tippen Sie anschließend auf **Speichern**, um die Änderungen zu speichern.

7. Optional: Wenn Sie den kostenlosen Versand für Versandkosten über einen bestimmten Geldwert hinaus ausschließen möchten, tippen Sie auf **Versandkosten** und aktivieren Sie **Versandkosten über einen bestimmten Betrag ausschließen**. Geben Sie die maximalen Versandkosten ein in das Feld **Betrag** ein.

8. Tippen Sie auf **Kundenberechtigung** und wählen Sie aus, für wen dieser Rabatt gelten soll: **Alle**, **Bestimmte Kundengruppen** oder **Bestimmte Kunden**.

    Tippen Sie auf **Hinzufügen** und wählen Sie die Kunden oder Kundengruppen aus, auf die Sie den Rabatt anwenden möchten. Tippen Sie auf **Fertig**, um Ihre Änderungen zu speichern.

    Kundenlisten geben die E-Mail-Adresse an, mit denen sie sich bei Ihrem Shop registriert haben. Wenn keine E-Mail-Adresse angegeben wurde, wird in der Liste die Telefonnummer des Kunden angezeigt.

    Um den Rabattanspruch eines einzelnen Kunden oder eine Kundengruppe zu löschen, tippen Sie auf **Bearbeiten** und heben Sie die Auswahl des Kunden oder der Kundengruppe auf.

    Weitere Informationen zum Erstellen von Kundengruppen finden Sie unter [_Kunden verwalten_](/manual/customers/manage-customers#create-customer-groups).

9. Die Rabattnutzung ist standardmäßig unbegrenzt. Wenn Sie die Rabattnutzung einschränken möchten, tippen Sie auf **Nutzungsbeschränkungen** und aktivieren Sie die Nutzungsbeschränkungsoptionen, die Sie auf Ihren Rabatt anwenden möchten:

    - Mit **Beschränken, wie oft dieser Rabattcode insgesamt verwendet werden kann** können Sie festlegen, wie oft ein Rabatt insgesamt verwendet werden kann. Wenn Sie beispielsweise ein Limit von 200 festlegen, wird der Rabattcode 200 Mal für Ihren Kundenstamm verwendet. Wenn Sie diese Einstellung wählen, können Kunden den Rabatt mehrmals verwenden.
    - **Auf eine Benutzung pro Kunde beschränken** verfolgt die E-Mails des Kunden, um den Rabatt auf eine Benutzung pro Kunde zu beschränken.

10. Tippen Sie auf **Aktive Daten**, um das Startdatum für den Rabatt festzulegen. Wenn Sie ein Enddatum für den Rabatt festlegen möchten, klicken Sie auf **Enddatum festlegen** und verwenden Sie den Kalender, um festzulegen, wann der Rabatt endet:

    ![Aktive Daten für Rabatt – iPhone](/manual/discounts/discount-dates-iphone.png)

    Wenn Sie kein Enddatum für Ihren Rabatt auswählen, hat er kein Ablaufdatum. Wenn der Rabatt nur für einen Tag gültig sein soll, wählen Sie den gleichen Kalendertag als Startdatum und Enddatum aus.

> Hinweis: Der Zeitpunkt, zu dem der Rabatt beginnt und endet, hängt von der [Zeitzone ab, die Sie im Shopify-Adminbereich ausgewählt haben](/manual/intro-to-shopify/initial-setup/setup-business-settings/#set-or-change-your-store-timezone). Wenn beispielsweise die Zeitzone Ihres Shops Eastern Standard Time ist und Sie als Startdatum den 26. November auswählen, beginnt Ihr Rabatt am 26. November um 12 Uhr EST.

11. Wenn Sie fertig sind, tippen Sie auf **Speichern**.

Der neue Rabatt wird jetzt in der Ansicht **Rabatte** unter **Shop** in der Shopify-App angezeigt. Um diesen Rabatt zu verteilen, können Sie den Code per E-Mail an Ihre Kunden senden oder in Ihrem Online-Shop anzeigen. Ihre Kunden müssen den Code beim Checkout eingeben, um den Rabatt zu erhalten.

----

{% comment %} Android-Abschnitt {% endcomment %}

1. Gehen Sie in der [Shopify App](https://www.shopify.com/install/detect) auf **Shop** > **Rabatte**.

2. Tippen Sie auf der Seite **Rabatte** auf die Schaltfläche `+`.

3. Geben Sie im Abschnitt **Rabattcode** einen Namen für den neuen Rabattcode ein (z. B. `freeshipping4smallorders`). Um einen zufälligen Rabattcode zu generieren, klicken Sie auf **Code generieren**.

    ![Rabattcodename für kostenlosen Versand – Android](/manual/discounts/discount-name-free-shipping-android.png)

> Hinweis: Vermeiden Sie die Verwendung von Sonderzeichen in Rabattnamen, damit Ihre Rabattnamen korrekt zur Checkout-URL Ihres Shops hinzugefügt werden.

4. Tippen Sie auf **Rabattart** und wählen Sie im Dropdown-Menü **Kostenloser Versand**.

5. Tippen Sie auf **Länder** und wählen Sie die Länder aus, für die dieser Rabatt gelten soll: **Alle Länder** oder **Bestimmte Länder**.

    Um den Rabatt auf bestimmte Länder zu beschränken, wählen Sie im Dropdown-Menü **Ausgewählte Länder**. Tippen Sie auf `+` neben **Länder**, um die Länderauswahl zu öffnen. Wählen Sie die Länder aus, für die Sie den Rabatt verfügbar machen möchten, und tippen Sie anschließend auf ✔, um die Änderungen zu speichern.

6. Optional: Wenn Sie den kostenlosen Versand für Versandkosten über einen bestimmten Geldwert hinaus ausschließen möchten, tippen Sie auf **Versandkosten** und aktivieren Sie **Versandkosten über einen bestimmten Betrag ausschließen**. Geben Sie die maximalen Versandkosten ein in das Feld **Betrag** ein.

7. Wenn Sie eine Mindestanforderung für den Rabatt festlegen möchten, tippen Sie auf **Mindestanforderungen** und wählen Sie eine Anforderung aus:

    - **Mindestabnahmebetrag** erfordert, dass Kunden einen Mindestbetrag ausgeben, um sich für den Rabatt zu qualifizieren.
    - **Mindeststückzahl** erfordert, dass Kunden eine Mindestanzahl von Produkten bestellen, um sich für den Rabatt zu qualifizieren.

> Hinweis: Wenn der Rabatt für ein bestimmtes Produkt oder eine bestimmte Kategorie gilt, tragen nur diese Artikel zu den Mindestkauf- oder Mengenbeträgen bei.

8. Tippen Sie auf **Kundenberechtigung** und wählen Sie aus, für wen dieser Rabatt gelten soll: **Alle**, **Bestimmte Kundengruppen** oder **Bestimmte Kunden**.

    Tippen Sie auf `+` und wählen Sie die Kunden oder Kundengruppen aus, auf die Sie den Rabatt anwenden möchten. Tippen Sie auf ✔, um Ihre Änderungen zu speichern.

    Kundenlisten geben die E-Mail-Adresse an, mit denen sie sich bei Ihrem Shop registriert haben. Wenn keine E-Mail-Adresse angegeben wurde, wird in der Liste die Telefonnummer des Kunden angezeigt.

    Um den Rabattanspruch eines einzelnen Kunden oder eine Kundengruppe zu löschen, tippen Sie auf das Stiftsymbol und heben Sie die Auswahl des Kunden oder der Kundengruppe auf.

    Weitere Informationen zum Erstellen von Kundengruppen finden Sie unter [_Kunden verwalten_](/manual/customers/manage-customers#create-customer-groups).

9. Die Rabattnutzung ist standardmäßig unbegrenzt. Wenn Sie die Rabattnutzung einschränken möchten, tippen Sie auf **Nutzungsbeschränkungen** und aktivieren Sie die Nutzungsbeschränkungsoptionen, die Sie auf Ihren Rabatt anwenden möchten:

    - Mit **Beschränken, wie oft dieser Rabattcode insgesamt verwendet werden kann** können Sie festlegen, wie oft ein Rabatt insgesamt verwendet werden kann. Wenn Sie beispielsweise ein Limit von 200 festlegen, wird der Rabattcode 200 Mal für Ihren Kundenstamm verwendet. Wenn Sie diese Einstellung wählen, können Kunden den Rabatt mehrmals verwenden.
    - **Auf eine Benutzung pro Kunde beschränken** verfolgt die E-Mails des Kunden, um den Rabatt auf eine Benutzung pro Kunde zu beschränken.

10. Tippen Sie auf **Aktive Daten**, um das Startdatum für den Rabatt festzulegen. Wenn Sie ein Enddatum für den Rabatt festlegen möchten, klicken Sie auf **Enddatum festlegen** und verwenden Sie den Kalender, um festzulegen, wann der Rabatt endet:

    ![Aktive Daten für Rabatt – Android](/manual/discounts/discount-active-dates-android.png)

    Wenn Sie kein Enddatum für Ihren Rabatt auswählen, hat er kein Ablaufdatum. Wenn der Rabatt nur für einen Tag gültig sein soll, wählen Sie den gleichen Kalendertag als Startdatum und Enddatum aus.

> Hinweis: Der Zeitpunkt, zu dem der Rabatt beginnt und endet, hängt von der [Zeitzone ab, die Sie im Shopify-Adminbereich ausgewählt haben](/manual/intro-to-shopify/initial-setup/setup-business-settings/#set-or-change-your-store-timezone). Wenn beispielsweise die Zeitzone Ihres Shops Eastern Standard Time ist und Sie als Startdatum den 26. November auswählen, beginnt Ihr Rabatt am 26. November um 12 Uhr EST.

11. Wenn Sie fertig sind, tippen Sie auf ✔.

Der neue Rabatt wird jetzt in der Ansicht **Rabatte** unter **Shop** in der Shopify-App angezeigt. Um diesen Rabatt zu verteilen, können Sie den Code per E-Mail an Ihre Kunden senden oder in Ihrem Online-Shop anzeigen. Ihre Kunden müssen den Code beim Checkout eingeben, um den Rabatt zu erhalten.

{% endsections %}
