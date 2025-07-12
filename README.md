# MyHome2
## English
- Automatically choose and uses a warp spell or an item.
- **NEW**: GearSwap integration prevents gear conflicts during warp item usage.

### Command
- `//mh` OR `//warp`
- `//mh all` OR `//warp all` will warp all characters.

### Features
- **GearSwap Compatibility**: Automatically disables GearSwap slots when using warp items to prevent gear swapping during the warp process
- **Multi-language Support**: Works with both English and Japanese FFXI clients
- **Intelligent Item Detection**: Searches all accessible bags and wardrobes
- **Recast Monitoring**: Checks item recast timers and availability
- **Multi-character Support**: Can warp all characters simultaneously

### Priorities
1. **Warp** <me> - require learned and main job or sub job BLM (100 MP)
2. **Warp II** <me> - require learned and main job or sub job BLM (150 MP)
3. **Warp Ring** - search inventory and wardrobes, temporarily disables `ring1` slot in GearSwap
4. **Treat Staff II** - search inventory and wardrobes, temporarily disables `main` slot in GearSwap
5. **Warp Cudgel** - search inventory and wardrobes, temporarily disables `main` slot in GearSwap
6. **Instant Warp** - search inventory (consumable item)

### GearSwap Integration
When using warp items, the addon will:
- Temporarily disable the relevant GearSwap slot (ring1, main, etc.)
- Wait for the item activation timer and usage to complete
- Re-enable the GearSwap slot after 7 seconds to ensure the warp finishes

This prevents GearSwap from swapping out your warp item due to status changes during the warp process.

---

## 日本語
- デジョンやデジョン系アイテムをリキャストに応じて自動で選択、使用します。
- **新機能**: GearSwap統合により、ワープアイテム使用中の装備競合を防止します。

### Command
- `//mh` または `//warp`
- `//mh all` または `//warp all` すべての文字をワープします。

### 機能
- **GearSwap互換性**: ワープアイテム使用時にGearSwapスロットを自動的に無効化し、ワープ中の装備変更を防止
- **多言語サポート**: 英語版・日本語版FFXIクライアント両方に対応
- **スマート検索**: アクセス可能な全てのバッグとワードローブを検索
- **リキャスト監視**: アイテムのリキャストタイマーと使用可能性をチェック
- **マルチキャラクター対応**: 全キャラクターを同時にワープ可能

### 優先順位
1. **デジョン** <me> - 習得済かつメインまたはサポートジョブが黒魔道士 (MP100)
2. **デジョンII** <me> - 習得済かつメインまたはサポートジョブが黒魔道士 (MP150)
3. **デジョンリング** - マイバッグ、またはワードローブ(1~4)を検索、GearSwapの`ring1`スロットを一時無効化
4. **トリートスタッフII** - マイバッグ、またはワードローブ(1~4)を検索、GearSwapの`main`スロットを一時無効化
5. **デジョンカジェル** - マイバッグ、またはワードローブ(1~4)を検索、GearSwapの`main`スロットを一時無効化
6. **呪符デジョン** - マイバッグを検索 (消耗品)

### GearSwap統合
ワープアイテム使用時、アドオンは以下を実行します：
- 関連するGearSwapスロット（ring1、mainなど）を一時的に無効化
- アイテムの発動タイマーと使用完了を待機
- ワープ完了確保のため7秒後にGearSwapスロットを再有効化

これにより、ワープ処理中のステータス変化によるGearSwapの装備変更を防止します。
