## 送料無料ディスカウントを作成する

送料無料を利用可能とする場合、送料無料ディスカウントを作成することができます。

送料無料ディスカウントが自動的に注文に適用されることはありません。ディスカウントを受け取るには、チェックアウト時にお客様がコードを入力する必要があります。注文価格に基づいて送料無料を自動的にお客様に提示するには、[配送料無料の料金を設定する](/manual/shipping/rates-and-methods/examples/#free-shipping-over-a-set-dollar-amount)必要があります。

> メモ: 管理画面の[**配送**](//www.shopify.com/admin/settings/shipping)ページで[配送料無料](/manual/shipping/rates-and-methods/examples/#free-shipping-over-a-set-dollar-amount)を設定してください。これは、設定した送料無料の条件を満たすすべての注文に適用されます。

{{ 'xh4DEZVkNuA' | youtube }}

{% include link-to-more-videos.md %}

#### 手順:

{% sections "Desktop, iPhone, Android" %}

{% comment %}デスクトップセクション{% endcomment %}

{% include admin_sidebar/discounts.md %}

1. **ディスカウント**ページから、**[ディスカウントを作成する]** をクリックします。

2. **[ディスカウントコード]** セクションに、新しいディスカウントコードの名前を入力します (例: `freeshipping4smallorders`)。ランダムのディスカウントコードを生成するには、**[コードを生成する]** をクリックします。

3. **[オプション]** セクションで、**送料無料**のディスカウントタイプを選択します。

4. **[国]** セクションでは、**[すべての国]** を選択したままにするか、ディスカウントを適用する国を選択します。

    特定の金額以上の送料として送料無料を除外する場合、**[一定額以上の送料を除外する]** にチェックを入れ、フィールドに金額を入力します。このディスカウントは送料のみに適用されるもので、注文金額とは関係ありません。

5. **[顧客のディスカウント条件]** セクションで、このディスカウントを適用するユーザーを **[全員]**、**[特定の顧客グループ]**、または **[特定の顧客]** から選択します。

    検索フィールドを使用して、ディスカウントを受け取る個人またはグループを選択します。お客様のリストには、ストア登録に使用したメールが表示されます。メールアドレスの提示がない場合、お客様の電話番号がリストに表示されます。

    お客様またはお客様のグループをディスカウント対象から除外するには、お客様の名前またはグループの名前の横にある **[X]** をクリックします。

    顧客グループの作成の詳細については、「[_顧客管理_](/manual/customers/manage-customers#create-customer-groups)」を参照してください。

6. ディスカウントの使用は、デフォルトでは無制限です。ディスカウントの使用を制限する場合、**[利用制限]** セクションのいずれかのオプションをチェックします。

    - **このディスカウントを合計で使用できる回数を制限する**と、ディスカウントを使用できる合計回数を設定できます。たとえば、制限を200回に設定すると、ディスカウントコードをお客様ベース全体で200回使用できます。この設定を選択すると、お客様はディスカウントを複数回使用できます。
    - **お客様1人につき1回に制限する**には、お客様のメールを追跡することで、ディスカウントの使用をお客様1人につき1回に制限します。

7. **[有効期間]** セクションのカレンダーを使用して、ディスカウントの開始日を設定します。ディスカウントの終了日を設定する場合、**[終了日を設定する]** をクリックし、カレンダーを使用してディスカウントがいつ終了するかを選択します。

    ![ディスカウントの日付](/manual/discounts/discount-active-dates.png)

    ディスカウントの終了日を選択しない場合、有効期限はありません。ディスカウントを1日のみ有効にする場合、開始日と終了日の両方で同じ営業日を選択します。

> メモ: ディスカウントの開始と終了の時間は、[管理画面で選択したタイムゾーン](/manual/intro-to-shopify/initial-setup/setup-business-settings/#set-or-change-your-store-timezone)によって異なります。たとえば、ストアがタイムゾーン東部標準時間の11月26日を開始日として選択すると、11月26日の午前12時にディスカウントが開始されます。

8. 完了したら **[ディスカウントを保存する]** をクリックします。

新しいディスカウントが管理画面の[**ディスカウント**](//www.shopify.com/admin/discounts)ページに表示されます。このディスカウントを配布するために、お客様にメールでコードを送信するか、オンラインストアに表示することができます。

----

{% comment %}iOSセクション{% endcomment %}

1. [Shopifyのアプリ](https://www.shopify.com/install/detect)で、**[ストア]** > **[ディスカウント]** の順に移動します。

2. **ディスカウント**ページで、[`+`] ボタンをタップします。

3. **[ディスカウントコード]** セクションに、新しいディスカウントコードの名前を入力します (例: `freeshipping4smallorders`)。ランダムディスカウントコードを生成するには、**[コードを生成する]** をタップします。

    ![ディスカウントコード名「送料無料」- iPhone](/manual/discounts/discount-name-shipping-iphone.png)

> メモ: ディスカウント名には特殊文字を使用しないでください。これにより、ストアのチェックアウトURLにディスカウント名が正しく追加されます。

4. **[ディスカウントの種類]** をタップし、**[送料無料]** を選択します。

5. ディスカウントの最小要件を設定する場合、**[最小要件]** をタップして要件を選択します。

    - **最小購入額**により、ディスカウントの対象となるために最低金額を消費することがお客様に求められます。
    - **最小購入数量**により、ディスカウントの対象となるための商品の最少数の注文がお客様に求められます。

> メモ: ディスカウントが特定の商品またはコレクションに適用される場合、そのようなアイテムのみが最小購入額または最小購入数量に関係します。

6. **[国]** をタップし、このディスカウントが適用される国を、**[すべての国]** または **[特定の国]** から選択します。

    ディスカウントを特定の国に制限するには、**[特定の国]** を選択し、**[追加]** をタップして国のセレクターを開きます。ディスカウントを有効にする国を選択し、**[保存]** をタップして変更を保存します。

7. オプション: 特定の金額以上の送料から送料無料を除外する場合、**[配送料]** をタップして、**[一定額以上の送料を除外する]** を有効にします。**[値]** フィールドに、許可する最大額の配送料を入力します。

8. **[お客様のディスカウント条件]** をタップして、このディスカウントを適用するユーザーを **[全員]**、**[特定の顧客グループ]**、または **[特定の顧客]** から選択します。

    **[追加]** をタップし、ディスカウントを適用するお客様またはお客様のグループを選択します。**[保存]** をタップして変更を保存します。

    お客様のリストには、ストア登録に使用したメールが表示されます。メールアドレスの提示がない場合、お客様の電話番号がリストに表示されます。

    個人のお客様またはお客様のグループをディスカウント対象から除外するには、**[編集]** をタップして、お客様またはお客様グループの選択を解除します。

    顧客グループの作成の詳細については、「[_顧客管理_](/manual/customers/manage-customers#create-customer-groups)」を参照してください。

9. ディスカウントの使用は、デフォルトでは無制限です。ディスカウントの使用を制限する場合、**[利用制限]** をタップし、ディスカウントに適用する利用制限オプションを有効にします。

    - **このディスカウントを合計で使用できる回数を制限する**と、ディスカウントを使用できる合計回数を設定できます。たとえば、制限を200回に設定すると、ディスカウントコードをお客様ベース全体で200回使用できます。この設定を選択すると、お客様はディスカウントを複数回使用できます。
    - **お客様1人につき1回に制限する**には、お客様のメールを追跡することで、ディスカウントの使用をお客様1人につき1回に制限します。

10. **[有効期間]** をタップして、ディスカウントの開始日を設定します。ディスカウントの終了日を設定する場合、**[終了日を設定する]** を有効にし、終了日のカレンダーを使用してディスカウントを終了する日付を選択します。

    ![ディスカウント有効期間 - iPhone](/manual/discounts/discount-dates-iphone.png)

    ディスカウントの終了日を選択しない場合、有効期限はありません。ディスカウントを1日のみ有効にする場合、開始日と終了日の両方で同じ営業日を選択します。

> メモ: ディスカウントの開始と終了の時間は、[管理画面で選択したタイムゾーン](/manual/intro-to-shopify/initial-setup/setup-business-settings/#set-or-change-your-store-timezone)によって異なります。たとえば、ストアがタイムゾーン東部標準時間の11月26日を開始日として選択すると、11月26日の午前12時にディスカウントが開始されます。

11. 完了したら **[保存]** をタップします。

新しいディスカウントがShopifyアプリの**ストア**の下の **[ディスカウント]** ビューに表示されます。このディスカウントを配布するために、お客様にコードをメールで送信するか、あるいはオンラインストアに表示することができます。ディスカウントを受け取るには、チェックアウト時にお客様がコードを入力する必要があります。

----

{% comment %} Androidセクション {% endcomment %}

1. [Shopifyのアプリ](https://www.shopify.com/install/detect)で、**[ストア]** > **[ディスカウント]** の順に移動します。

2. **ディスカウント**ページで、[`+`] ボタンをタップします。

3. **[ディスカウントコード]** セクションに、新しいディスカウントコードの名前を入力します (例: `freeshipping4smallorders`)。ランダムのディスカウントコードを生成するには、**[コードを生成する]** をタップします。

    ![ディスカウントコード名「配送」- Android](/manual/discounts/discount-name-free-shipping-android.png)

> メモ: ディスカウント名には特殊文字を使用しないでください。これにより、ストアのチェックアウトURLにディスカウント名が正しく追加されます。

4. **[ディスカウントの種類]** をタップし、ドロップダウンメニューから **[送料無料]** を選択します。

5. **[国]** をタップし、このディスカウントが適用される国を、**[すべての国]** または **[特定の国]** から選択します。

    ディスカウントを選択された国に適用するには、ドロップダウンメニューから **[選択された国]** を選択します。**[国]** の横の [`+`] をタップして、国セレクターを開きます。ディスカウントを有効にする国を選択し、[✔] をタップして変更を保存します。

6. オプション: 特定の金額以上の送料から送料無料を除外する場合、**[配送料]** をタップして、**[一定額以上の送料を除外する]** を有効にします。**[値]** フィールドに、許可する最大額の配送料を入力します。

7. ディスカウントの最小要件を設定する場合、**[最小要件]** をタップして要件を選択します。

    - **最小購入額**により、ディスカウントの対象となるために最低金額を消費することがお客様に求められます。
    - **最小購入数量**により、ディスカウントの対象となるための商品の最少数の注文がお客様に求められます。

> メモ: ディスカウントが特定の商品またはコレクションに適用される場合、そのようなアイテムのみが最小購入額または最小購入数量に関係します。

8. **[お客様のディスカウント条件]** をタップして、このディスカウントを適用するユーザーを **[全員]**、**[特定の顧客グループ]**、または **[特定の顧客]** から選択します。

    [`+`] をタップし、ディスカウントを適用するお客様またはお客様のグループを選択します。[✔] をタップして変更を保存します。

    お客様のリストには、ストア登録に使用したメールが表示されます。メールアドレスの提示がない場合、お客様の電話番号がリストに表示されます。

    個人のお客様またはお客様のグループをディスカウント対象から除外するには、[鉛筆] アイコンをタップしてお客様またはお客様グループの選択を解除します。

    顧客グループの作成の詳細については、「[_顧客管理_](/manual/customers/manage-customers#create-customer-groups)」を参照してください。

9. ディスカウントの使用は、デフォルトでは無制限です。ディスカウントの使用を制限する場合、**[利用制限]** をタップし、ディスカウントに適用する利用制限オプションを有効にします。

    - **このディスカウントを合計で使用できる回数を制限する**と、ディスカウントを使用できる合計回数を設定できます。たとえば、制限を200回に設定すると、ディスカウントコードをお客様ベース全体で200回使用できます。この設定を選択すると、お客様はディスカウントを複数回使用できます。
    - **お客様1人につき1回に制限する**には、お客様のメールを追跡することで、ディスカウントの使用をお客様1人につき1回に制限します。

10. **[有効期間]** をタップして、ディスカウントの開始日を設定します。ディスカウントの終了日を設定する場合、**[終了日を設定する]** を有効にし、終了日のカレンダーを使用してディスカウントを終了する日付を選択します。

    ![ディスカウント有効期間 - Android](/manual/discounts/discount-active-dates-android.png)

    ディスカウントの終了日を選択しない場合、有効期限はありません。ディスカウントを1日のみ有効にする場合、開始日と終了日の両方で同じ営業日を選択します。

> メモ: ディスカウントの開始と終了の時間は、[管理画面で選択したタイムゾーン](/manual/intro-to-shopify/initial-setup/setup-business-settings/#set-or-change-your-store-timezone)によって異なります。たとえば、ストアがタイムゾーン東部標準時間の11月26日を開始日として選択すると、11月26日の午前12時にディスカウントが開始されます。

11. 完了したら、[✔] をタップします。

新しいディスカウントがShopifyアプリの**ストア**の下の **[ディスカウント]** ビューに表示されます。このディスカウントを配布するために、お客様にコードをメールで送信するか、あるいはオンラインストアに表示することができます。ディスカウントを受け取るには、チェックアウト時にお客様がコードを入力する必要があります。

{% endsections %}