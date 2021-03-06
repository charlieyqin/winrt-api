---
-api-id: T:Windows.ApplicationModel.Wallet.WalletVerb
-api-type: winrt class
---

<!-- Class syntax.
public class WalletVerb : Windows.ApplicationModel.Wallet.IWalletVerb
-->

# Windows.ApplicationModel.Wallet.WalletVerb

## -description
Represents a wallet verb, which is potentially used for app activation. This is a string suitable for UI that is descriptive of the action.

## -remarks
You can associate verbs, such as "register", "pay with" with an item in the wallet. When the user selects a verb, your app is activated. The selected verb is passed to an app as part of activation (in the [WalletActionActivatedEventArgs](../windows.applicationmodel.activation/walletactionactivatedeventargs.md) data, as the [ActionId](../windows.applicationmodel.activation/walletactionactivatedeventargs_actionid.md) value, and [ActionKind](../windows.applicationmodel.activation/walletactionactivatedeventargs_actionkind.md) will be **Verb**).

> [!NOTE]
> JavaScript apps use [WebUIWalletActionActivatedEventArgs](../windows.ui.webui/webuiwalletactionactivatedeventargs.md).

A [WalletVerb](walletverb.md) object represents the individual items for the [WalletItem.Verbs](walletitem_verbs.md) property.

The verb is a cue to the app of which UI to display on activation, which might be specific to the verb that was chosen by the user.

For more info on using **Wallet** activation, see the "Handling app activation by Wallet " section of [Quickstart: Using the   APIs](http://msdn.microsoft.com/library/4312628c-37a3-48a7-b41f-14605d478cf7).

## -examples

## -see-also
[WalletItem.Verbs](walletitem_verbs.md), [WalletItem](walletitem.md)