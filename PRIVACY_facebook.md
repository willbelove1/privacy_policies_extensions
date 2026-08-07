# Chính sách quyền riêng tư — FB PowerSuite

**Có hiệu lực từ:** 07/08/2026
**Nhà phát triển:** Lucas & Dad (Tân Thanh Company)

## Tóm tắt

FB PowerSuite **không thu thập, không lưu trữ, và không truyền bất kỳ dữ liệu cá nhân nào** của người dùng ra bên ngoài trình duyệt. Toàn bộ xử lý (lọc feed, chặn popup đăng nhập, xoá tham số theo dõi, bật HD Messenger, tải ảnh, mở rộng bố cục) diễn ra hoàn toàn cục bộ trên máy của bạn.

## Dữ liệu chúng tôi lưu — chỉ trên thiết bị của bạn

Extension lưu các lựa chọn cấu hình sau bằng `chrome.storage.local` (API lưu trữ cục bộ của Chrome):

- Trạng thái bật/tắt của từng module (chặn đăng nhập, xoá fbclid, Messenger HD, tải ảnh, mở rộng layout, engine lọc feed)
- Số cột hiển thị đã chọn cho bố cục nhiều cột
- Trạng thái giao diện nhỏ (đã thu gọn banner hay chưa, đã xem hướng dẫn hay chưa)

Dữ liệu này **không rời khỏi trình duyệt của bạn** — không được gửi lên bất kỳ máy chủ nào của nhà phát triển hay bên thứ ba nào. Nó chỉ tồn tại trên thiết bị bạn cài extension và sẽ bị xoá nếu bạn gỡ cài đặt extension.

## Dữ liệu chúng tôi KHÔNG thu thập

Chúng tôi không thu thập, không theo dõi, và không lưu trữ:

- Tên, email, số điện thoại, hay bất kỳ thông tin định danh cá nhân nào
- Nội dung bài viết, tin nhắn, ảnh, video trên Facebook/Messenger
- Lịch sử duyệt web, lịch sử tìm kiếm
- Vị trí địa lý
- Bất kỳ hình thức phân tích (analytics) hay số liệu sử dụng nào

Không có quảng cáo, không có theo dõi bên thứ ba, không có việc bán hay chia sẻ dữ liệu dưới bất kỳ hình thức nào.

## Quyền truy cập trình duyệt và mục đích sử dụng

| Quyền | Mục đích |
|---|---|
| `storage` | Lưu cấu hình bật/tắt các module cục bộ trên máy bạn |
| `activeTab` | Reload tab hiện tại khi bạn bấm "Reload Tab" trong popup, sau khi đổi một cài đặt cần tải lại trang |
| `contextMenus` | Thêm mục menu chuột phải "Open Clean My Feeds Settings" trên facebook.com |
| Quyền truy cập `*.facebook.com`, `*.messenger.com` | Cho phép content script chạy trên hai domain này để thực hiện các tính năng của extension (lọc feed, chặn popup, xoá tracking, HD Messenger) |

Extension **không yêu cầu và không có quyền truy cập** vào bất kỳ website nào khác ngoài Facebook và Messenger.

## Thành phần mã nguồn mở

Một phần engine lọc feed và logic tải ảnh của FB PowerSuite dựa trên các dự án mã nguồn mở của bên thứ ba (giấy phép GPL-3.0 và MIT). Các thành phần này chạy hoàn toàn cục bộ trong trình duyệt của bạn giống như phần còn lại của extension — không có hành vi thu thập hay gửi dữ liệu nào khác với phần được mô tả ở trên. Chi tiết ghi công đầy đủ có trong file `NOTICE.md` đi kèm gói cài đặt.

## Trẻ em

FB PowerSuite không hướng đến và không được thiết kế dành cho trẻ em dưới 13 tuổi.

## Thay đổi chính sách

Nếu chính sách này thay đổi, bản cập nhật sẽ được đăng tại cùng địa chỉ URL này kèm ngày cập nhật mới.

## Liên hệ

Mọi câu hỏi về chính sách quyền riêng tư này, vui lòng liên hệ: **[điền email hoặc link liên hệ của bạn tại đây]**

---

# Privacy Policy — FB PowerSuite (English)

**Effective date:** August 7, 2026
**Developer:** Lucas & Dad (Tân Thanh Company)

## Summary

FB PowerSuite **does not collect, store, or transmit any personal data**. All functionality (feed cleaning, login-popup blocking, tracking-parameter removal, Messenger HD, photo download, multi-column layout) runs entirely locally in your browser.

## What we store — locally on your device only

The extension stores the following configuration choices using Chrome's local storage API (`chrome.storage.local`):

- On/off state of each module (login blocker, fbclid cleaner, Messenger HD, photo downloader, layout enhancer, feed-cleaning engine)
- Your chosen column count for the multi-column layout
- Minor UI state (whether the status banner is minimized, whether you've seen the onboarding tip)

This data **never leaves your browser** — it is not sent to any server operated by the developer or any third party. It exists only on the device where you installed the extension and is deleted when you uninstall it.

## What we do NOT collect

We do not collect, track, or store:

- Your name, email, phone number, or any personally identifiable information
- Facebook/Messenger post content, messages, photos, or videos
- Browsing history or search history
- Location data
- Any analytics or usage metrics

There is no advertising, no third-party tracking, and no data is sold or shared in any form.

## Permissions and their purpose

| Permission | Purpose |
|---|---|
| `storage` | Store module on/off settings locally on your device |
| `activeTab` | Reload the current tab when you click "Reload Tab" in the popup, after changing a setting that needs a reload |
| `contextMenus` | Add an "Open Clean My Feeds Settings" right-click menu item on facebook.com |
| Host access to `*.facebook.com`, `*.messenger.com` | Lets the content script run on these two domains to power the extension's features |

The extension does **not** request or have access to any website other than Facebook and Messenger.

## Open-source components

Parts of the feed-cleaning engine and photo-download logic are based on third-party open-source projects (GPL-3.0 and MIT licensed). These components run entirely locally in your browser, same as the rest of the extension — they introduce no additional data collection or transmission beyond what's described above. Full attribution is included as `NOTICE.md` in the extension package.

## Children's privacy

FB PowerSuite is not directed at, and is not designed for, children under 13.

## Changes to this policy

Any changes to this policy will be posted at this same URL with an updated effective date.

## Contact

For questions about this privacy policy, contact: **[insert your contact email or link here]**
