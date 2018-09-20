# <a name="whats-changed-in-the-javascript-api-for-office"></a><span data-ttu-id="b549a-101">JavaScript API for Office の変更点</span><span class="sxs-lookup"><span data-stu-id="b549a-101">What's changed in the JavaScript API for Office</span></span>

<span data-ttu-id="b549a-102">JavaScript API for Office は、Office アドインの機能を拡張するため、オブジェクト、メソッド、プロパティ、イベント、列挙体の新規追加や更新によって定期的に更新が加えられています。新規および更新された API のメンバーを確認するには、次のリンクを参照してください。</span><span class="sxs-lookup"><span data-stu-id="b549a-102">The JavaScript API for Office is periodically updated with new and updated objects, methods, properties, events and enumerations to extend the functionality of your Office Add-ins. Use the links below to see the new and updated API members.</span></span>

<span data-ttu-id="b549a-103">新しい API メンバーを使用してアドインを開発するには、[プロジェクトで JavaScript API for Office ファイルを更新する](https://docs.microsoft.com/office/dev/add-ins/develop/update-your-javascript-api-for-office-and-manifest-schema-version)必要があります。</span><span class="sxs-lookup"><span data-stu-id="b549a-103">To develop add-ins using new API members, you need to [update the JavaScript API for Office files in your project](https://docs.microsoft.com/office/dev/add-ins/develop/update-your-javascript-api-for-office-and-manifest-schema-version).</span></span>

<span data-ttu-id="b549a-104">前回の更新から変更されていない API メンバーを含むすべての API メンバーを表示するには、「[JavaScript API for Office](javascript-api-for-office.md)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="b549a-104">To view all API members including those that are unchanged from previous updates, see [JavaScript API for Office](javascript-api-for-office.md).</span></span>

## <a name="new-and-updated-apis"></a><span data-ttu-id="b549a-105">新規および更新された API</span><span class="sxs-lookup"><span data-stu-id="b549a-105">New and updated APIs</span></span>

### <a name="new-and-updated-objects"></a><span data-ttu-id="b549a-106">新規オブジェクトと更新されたオブジェクト</span><span class="sxs-lookup"><span data-stu-id="b549a-106">New and updated objects</span></span>

|<span data-ttu-id="b549a-107">**オブジェクト**</span><span class="sxs-lookup"><span data-stu-id="b549a-107">**Object**</span></span>|<span data-ttu-id="b549a-108">**説明**</span><span class="sxs-lookup"><span data-stu-id="b549a-108">**Description**</span></span>|<span data-ttu-id="b549a-109">**追加または更新されたバージョン**</span><span class="sxs-lookup"><span data-stu-id="b549a-109">**Version added or updated**</span></span>|
|:-----|:-----|:-----|
|`Item`|<span data-ttu-id="b549a-110">次に対して更新および追加が行われました。</span><span class="sxs-lookup"><span data-stu-id="b549a-110">Updates and additions to:</span></span><br><ul><li><p><span data-ttu-id="b549a-111">`getSelectedDataAsync`と`setSelectedDataAsync`ユーザーの選択範囲を取得し、件名、メッセージまたは予定の本文に上書きすることをサポートするメソッドです。</span><span class="sxs-lookup"><span data-stu-id="b549a-111">The `getSelectedDataAsync` and `setSelectedDataAsync` methods to support getting the user's selection and overwriting it in the subject and body  of a message or appointment.</span></span></p></li><li><p><span data-ttu-id="b549a-112">`displayReplyAllForm`と`displayReplyForm`予定の返信用フォームの添付ファイルの追加をサポートするためのメソッドです。</span><span class="sxs-lookup"><span data-stu-id="b549a-112">The `displayReplyAllForm` and `displayReplyForm` methods to support adding an attachment to the reply form of an appointment.</span></span></p></li></ul>|<span data-ttu-id="b549a-113">Mailbox 1.2</span><span class="sxs-lookup"><span data-stu-id="b549a-113">Mailbox 1.2</span></span>|
|`Item`|<span data-ttu-id="b549a-114">新規作成モードの Outlook アドインを作成するためのメソッドとフィールドを含めるよう更新されました。</span><span class="sxs-lookup"><span data-stu-id="b549a-114">Updated to include methods and fields for creating compose mode Outlook add-ins.</span></span> |<span data-ttu-id="b549a-115">1.1</span><span class="sxs-lookup"><span data-stu-id="b549a-115">1.1</span></span>|
|`Binding`|<span data-ttu-id="b549a-116">Access 用コンテンツ アドインにおけるテーブル バインドをサポートするよう更新されました。</span><span class="sxs-lookup"><span data-stu-id="b549a-116">Updated to support table binding in content add-ins for Access.</span></span>|<span data-ttu-id="b549a-117">1.1</span><span class="sxs-lookup"><span data-stu-id="b549a-117">1.1</span></span>|
|`Bindings`|<span data-ttu-id="b549a-118">Access 用コンテンツ アドインにおけるテーブル バインドをサポートするよう更新されました。</span><span class="sxs-lookup"><span data-stu-id="b549a-118">Updated to support table binding in content add-ins for Access.</span></span>|<span data-ttu-id="b549a-119">1.1</span><span class="sxs-lookup"><span data-stu-id="b549a-119">1.1</span></span>|
|`Body`|<span data-ttu-id="b549a-120">新規作成モードの Outlook アドインでメッセージや予定の本文を作成および編集できるよう追加されました。</span><span class="sxs-lookup"><span data-stu-id="b549a-120">Added to enable creating and editing the body of a message or appointment in compose mode Outlook add-ins.</span></span>|<span data-ttu-id="b549a-121">1.1</span><span class="sxs-lookup"><span data-stu-id="b549a-121">1.1</span></span>|
|`Document`|<span data-ttu-id="b549a-122">次に対して更新および追加が行われました。</span><span class="sxs-lookup"><span data-stu-id="b549a-122">Updates and additions to:</span></span> <ul><li><p><span data-ttu-id="b549a-123">Access 用のコンテンツ アドインで <a href="https://docs.microsoft.com/javascript/api/office/office.document?view=office-js" target="_blank">mode</a>、<a href="https://docs.microsoft.com/javascript/api/office/office.document?view=office-js#settings" target="_blank">settings</a>、および <a href="https://docs.microsoft.com/javascript/api/office/office.document?view=office-js" target="_blank">url</a> の各プロパティをサポートします。</span><span class="sxs-lookup"><span data-stu-id="b549a-123">Support <a href="https://docs.microsoft.com/javascript/api/office/office.document?view=office-js" target="_blank">mode</a>, <a href="https://docs.microsoft.com/javascript/api/office/office.document?view=office-js#settings" target="_blank">settings</a>, and <a href="https://docs.microsoft.com/javascript/api/office/office.document?view=office-js" target="_blank">url</a> properties in content add-ins for Access.</span></span></p></li><li><p><span data-ttu-id="b549a-124">PowerPoint および Word 用アドインで、<a href="https://docs.microsoft.com/javascript/api/office/office.document?view=office-js#getfileasync-filetype--options--callback-" target="_blank">getFileAsync</a> メソッドを使用してドキュメントを PDF として取得します。</span><span class="sxs-lookup"><span data-stu-id="b549a-124">Get the document as PDF with the <a href="https://docs.microsoft.com/javascript/api/office/office.document?view=office-js#getfileasync-filetype--options--callback-" target="_blank">getFileAsync</a> method in add-ins for PowerPoint and Word.</span></span></p></li><li><p><span data-ttu-id="b549a-125">Excel、PowerPoint、および Word 用アドインで、<a href="https://docs.microsoft.com/javascript/api/office/office.document?view=office-js#getfilepropertiesasync-options--callback-" target="_blank">getFileProperties</a> メソッドを使用してファイルのプロパティを取得します。</span><span class="sxs-lookup"><span data-stu-id="b549a-125">Get file properties with the <a href="https://docs.microsoft.com/javascript/api/office/office.document?view=office-js#getfilepropertiesasync-options--callback-" target="_blank">getFileProperties</a> method in add-ins for Excel, PowerPoint, and Word.</span></span></p></li><li><p><span data-ttu-id="b549a-126">Excel および PowerPoint 用アドインで、<a href="https://docs.microsoft.com/javascript/api/office/office.document?view=office-js#gotobyidasync-id--gototype--options--callback-" target="_blank">goToByIdAsync</a> メソッドを使用して、ドキュメント内の場所とオブジェクトに移動します。</span><span class="sxs-lookup"><span data-stu-id="b549a-126">Navigate to locations and objects within the document with the <a href="https://docs.microsoft.com/javascript/api/office/office.document?view=office-js#gotobyidasync-id--gototype--options--callback-" target="_blank">goToByIdAsync</a> method in add-ins for Excel and PowerPoint.</span></span></p></li><li><p><span data-ttu-id="b549a-127">PowerPoint 用アドインで、<a href="https://docs.microsoft.com/javascript/api/office/office.document?view=office-js#getselecteddataasync-coerciontype--options--callback-" target="_blank">getSelectedDataAsync</a> メソッドを使用して (新しい <span class="keyword">Office.CoercionType.SlideRange</span><a href="https://docs.microsoft.com/javascript/api/office/office.coerciontype?view=office-js" target="_blank">coercionType</a> 列挙体を指定した場合)、選択したスライドの ID、タイトル、およびインデックスを取得します。</span><span class="sxs-lookup"><span data-stu-id="b549a-127">Get the id, title, and index for selected slides with the <a href="https://docs.microsoft.com/javascript/api/office/office.document?view=office-js#getselecteddataasync-coerciontype--options--callback-" target="_blank">getSelectedDataAsync</a> method (when you specify the new <span class="keyword">Office.CoercionType.SlideRange</span><a href="https://docs.microsoft.com/javascript/api/office/office.coerciontype?view=office-js" target="_blank">coercionType</a> enum) in add-ins for PowerPoint.</span></span></p></li></ul>|<span data-ttu-id="b549a-128">1.1</span><span class="sxs-lookup"><span data-stu-id="b549a-128">1.1</span></span>|
|`Location`|<span data-ttu-id="b549a-129">新規作成モードの Outlook アドインで予定の場所を設定できるよう追加されました。</span><span class="sxs-lookup"><span data-stu-id="b549a-129">Added to enable setting the location of an appointment in compose mode Outlook add-ins.</span></span>|<span data-ttu-id="b549a-130">1.1</span><span class="sxs-lookup"><span data-stu-id="b549a-130">1.1</span></span>|
|`Office`|<span data-ttu-id="b549a-131">Access 用コンテンツ アドインにおけるバインドの取得をサポートするよう select メソッドが更新されました。</span><span class="sxs-lookup"><span data-stu-id="b549a-131">Updated the select method to support getting bindings in content add-ins for Access.</span></span>|<span data-ttu-id="b549a-132">1.1</span><span class="sxs-lookup"><span data-stu-id="b549a-132">1.1</span></span>|
|`Recipients`|<span data-ttu-id="b549a-133">新規作成モードでメッセージや予定の受信者を取得および設定できるよう追加されました。</span><span class="sxs-lookup"><span data-stu-id="b549a-133">Added to enable getting and setting the recipients of a message or appointment in compose mode.</span></span>|<span data-ttu-id="b549a-134">1.1</span><span class="sxs-lookup"><span data-stu-id="b549a-134">1.1</span></span>|
|`Settings`|<span data-ttu-id="b549a-135">Access 用コンテンツ アドインにおけるカスタム設定の作成をサポートするよう更新されました。</span><span class="sxs-lookup"><span data-stu-id="b549a-135">Updated to support creating custom settings in content add-ins for Access.</span></span>|<span data-ttu-id="b549a-136">1.1</span><span class="sxs-lookup"><span data-stu-id="b549a-136">1.1</span></span>|
|`Subject`|<span data-ttu-id="b549a-137">新規作成モードの Outlook アドインでメッセージや予定の件名を取得および設定できるよう追加されました。</span><span class="sxs-lookup"><span data-stu-id="b549a-137">Added to enable getting and setting the subject of a message or appointment in compose mode Outlook add-ins.</span></span>|<span data-ttu-id="b549a-138">1.1</span><span class="sxs-lookup"><span data-stu-id="b549a-138">1.1</span></span>|
|`Time`|<span data-ttu-id="b549a-139">新規作成モードの Outlook アドインで予定の開始時刻および終了時刻を取得および設定できるよう追加されました。</span><span class="sxs-lookup"><span data-stu-id="b549a-139">Added to enable getting and setting the start and end time of an appointment in compose mode Outlook add-ins.</span></span>|<span data-ttu-id="b549a-140">1.1</span><span class="sxs-lookup"><span data-stu-id="b549a-140">1.1</span></span>|

### <a name="new-and-updated-enumerations"></a><span data-ttu-id="b549a-141">新規列挙体および更新された列挙体</span><span class="sxs-lookup"><span data-stu-id="b549a-141">New and updated enumerations</span></span>

|<span data-ttu-id="b549a-142">**オブジェクト**</span><span class="sxs-lookup"><span data-stu-id="b549a-142">**Object**</span></span>|<span data-ttu-id="b549a-143">**説明**</span><span class="sxs-lookup"><span data-stu-id="b549a-143">**Description**</span></span>|<span data-ttu-id="b549a-144">**Version**</span><span class="sxs-lookup"><span data-stu-id="b549a-144">**Version**</span></span>|
|:-----|:-----|:-----|
|`ActiveView`|<span data-ttu-id="b549a-145">ユーザーがドキュメントを編集できるかどうかなど、ドキュメントのアクティブなビューの状態を示します。PowerPoint 用アドインで、ユーザーがプレゼンテーション ( **スライド ショー**) を閲覧しているのか、スライドを編集しているのかを判断できるように追加されました。</span><span class="sxs-lookup"><span data-stu-id="b549a-145">Specifies the state of the active view of the document, for example, whether the user can edit the document.Added so that add-ins for PowerPoint can determine if the users is viewing the presentation ( **Slide Show**) or editing slides.</span></span> |<span data-ttu-id="b549a-146">1.1</span><span class="sxs-lookup"><span data-stu-id="b549a-146">1.1</span></span>|
|`CoercionType`|<span data-ttu-id="b549a-147">PowerPoint 用アドインで、**getSelectedDataAsync** メソッドを使用して選択されたスライドの範囲の取得をサポートするよう **Office.CoercionType.SlideRange** が更新されました。</span><span class="sxs-lookup"><span data-stu-id="b549a-147">Updated with  **Office.CoercionType.SlideRange** to support getting the selected slide range with the **getSelectedDataAsync** method in add-ins for PowerPoint.</span></span>|<span data-ttu-id="b549a-148">1.1</span><span class="sxs-lookup"><span data-stu-id="b549a-148">1.1</span></span>|
|`EventType`|<span data-ttu-id="b549a-149">新しい ActiveViewChanged イベントを含めるよう更新されました。</span><span class="sxs-lookup"><span data-stu-id="b549a-149">Updated to include the new ActiveViewChanged event.</span></span>|<span data-ttu-id="b549a-150">1.1</span><span class="sxs-lookup"><span data-stu-id="b549a-150">1.1</span></span>|
|`FileType`|<span data-ttu-id="b549a-151">PDF 形式での出力を指定するよう更新されました。</span><span class="sxs-lookup"><span data-stu-id="b549a-151">Updated to specify output in PDF format.</span></span>|<span data-ttu-id="b549a-152">1.1</span><span class="sxs-lookup"><span data-stu-id="b549a-152">1.1</span></span>|
|`GoToType`|<span data-ttu-id="b549a-153">ドキュメントの移動先の場所またはオブジェクトを指定するよう追加されました。</span><span class="sxs-lookup"><span data-stu-id="b549a-153">Added to specify the place or object in the document to go to.</span></span>|<span data-ttu-id="b549a-154">1.1</span><span class="sxs-lookup"><span data-stu-id="b549a-154">1.1</span></span>|
