# <a name="outlook-add-in-api-requirement-set-16"></a><span data-ttu-id="65a19-101">Outlook アドイン API 要件は、1.6 を設定します。</span><span class="sxs-lookup"><span data-stu-id="65a19-101">Outlook add-in API requirement set 1.6</span></span>

<span data-ttu-id="65a19-102">JavaScript API for Office の Outlook アドイン API サブセットには、Outlook アドインで利用できるオブジェクト、メソッド、プロパティ、イベントが含まれます。</span><span class="sxs-lookup"><span data-stu-id="65a19-102">The Outlook add-in API subset of the JavaScript API for Office includes objects, methods, properties and events that you can use in an Outlook add-in.</span></span>

## <a name="whats-new-in-16"></a><span data-ttu-id="65a19-103">1.6 の新機能は何ですか。</span><span class="sxs-lookup"><span data-stu-id="65a19-103">What's new in 1.6?</span></span>

<span data-ttu-id="65a19-104">要件セット 1.6 には、すべての[要件は 1.5、設定](../requirement-set-1.5/outlook-requirement-set-1.5.md)の機能が含まれています。</span><span class="sxs-lookup"><span data-stu-id="65a19-104">Requirement set 1.6 includes all of the features of [Requirement set 1.5](../requirement-set-1.5/outlook-requirement-set-1.5.md).</span></span> <span data-ttu-id="65a19-105">それは、次の機能を追加します。</span><span class="sxs-lookup"><span data-stu-id="65a19-105">It added the following features.</span></span>

- <span data-ttu-id="65a19-106">追加された Api を使用するアドインのコンテキスト、エンティティを取得するか、正規表現は、アドインをアクティブにするのには、ユーザーが選択されていると一致します。</span><span class="sxs-lookup"><span data-stu-id="65a19-106">Added new APIs for contextual add-ins to get the entity or RegEx match that the user selected to activate the add-in.</span></span>
- <span data-ttu-id="65a19-107">新しいメッセージ フォームを開くに新しい API を追加します。</span><span class="sxs-lookup"><span data-stu-id="65a19-107">Added a new API to open a new message form.</span></span>
- <span data-ttu-id="65a19-108">アドインをユーザーのメールボックスのアカウントの種類を決定するための機能を追加します。</span><span class="sxs-lookup"><span data-stu-id="65a19-108">Added the ability for the add-in to determine the account type of the user's mailbox.</span></span>

### <a name="change-log"></a><span data-ttu-id="65a19-109">変更ログ</span><span class="sxs-lookup"><span data-stu-id="65a19-109">Change log</span></span>

- <span data-ttu-id="65a19-110">[Office.context.mailbox.item.getSelectedEntities](office.context.mailbox.item.md#getselectedentities--entitiesjavascriptapioutlook16officeentities)を追加: については、ユーザーが選択されて強調表示された一致するエンティティを取得する新しい関数を追加します。</span><span class="sxs-lookup"><span data-stu-id="65a19-110">Added [Office.context.mailbox.item.getSelectedEntities](office.context.mailbox.item.md#getselectedentities--entitiesjavascriptapioutlook16officeentities): Adds a new function that gets the entities found in a highlighted match a user has selected.</span></span> <span data-ttu-id="65a19-111">強調表示された一致は、コンテキスト アドインに適用されます。</span><span class="sxs-lookup"><span data-stu-id="65a19-111">Highlighted matches apply to contextual add-ins.</span></span>
- <span data-ttu-id="65a19-112">[Office.context.mailbox.item.getSelectedRegExMatches](office.context.mailbox.item.md#getselectedregexmatches--object)を追加: で強調表示されている一致するマニフェストの XML ファイルで定義されている正規表現に一致する文字列の値を返す新しい関数を追加します。</span><span class="sxs-lookup"><span data-stu-id="65a19-112">Added [Office.context.mailbox.item.getSelectedRegExMatches](office.context.mailbox.item.md#getselectedregexmatches--object): Adds a new function that returns string values in a highlighted match that match the regular expressions defined in the manifest XML file.</span></span> <span data-ttu-id="65a19-113">強調表示された一致は、コンテキスト アドインに適用されます。</span><span class="sxs-lookup"><span data-stu-id="65a19-113">Highlighted matches apply to contextual add-ins.</span></span>
- <span data-ttu-id="65a19-114">[Office.context.mailbox.displayNewMessageForm](office.context.mailbox.md#displaynewmessageformparameters)を追加: 新しいメッセージ フォームを表示する新しい関数を追加します。</span><span class="sxs-lookup"><span data-stu-id="65a19-114">Added [Office.context.mailbox.displayNewMessageForm](office.context.mailbox.md#displaynewmessageformparameters): Adds a new function that opens a new message form.</span></span>
- <span data-ttu-id="65a19-115">[Office.context.mailbox.userProfile.accountType](office.context.mailbox.userprofile.md#accounttype-string)を追加する: ユーザーのアカウントの種類を示すユーザー プロファイルに新しいメンバーを追加します。</span><span class="sxs-lookup"><span data-stu-id="65a19-115">Added [Office.context.mailbox.userProfile.accountType](office.context.mailbox.userprofile.md#accounttype-string): Adds a new member to the user profile that indicates the type of the user's account.</span></span>

## <a name="see-also"></a><span data-ttu-id="65a19-116">関連項目</span><span class="sxs-lookup"><span data-stu-id="65a19-116">See also</span></span>

- [<span data-ttu-id="65a19-117">Outlook アドイン</span><span class="sxs-lookup"><span data-stu-id="65a19-117">Outlook add-ins</span></span>](https://docs.microsoft.com/outlook/add-ins/)
- [<span data-ttu-id="65a19-118">Outlook アドインのコード サンプル</span><span class="sxs-lookup"><span data-stu-id="65a19-118">Outlook add-in code samples</span></span>](https://developer.microsoft.com/outlook/gallery/?filterBy=Outlook,Samples,Add-ins)
- [<span data-ttu-id="65a19-119">作業の開始</span><span class="sxs-lookup"><span data-stu-id="65a19-119">Get started</span></span>](https://docs.microsoft.com/outlook/add-ins/quick-start)