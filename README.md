<img width="200"  alt="c032b64d-be9a-4bdb-a14a-20ca3ffce8ef" src="https://github.com/user-attachments/assets/a846cf11-32a6-4d08-b89c-326e3d68fb67" />
<img width="200"  alt="e6707d1a-aaae-47b2-859b-6e260cc96d99" src="https://github.com/user-attachments/assets/f124b35c-a351-4cfb-be12-376e7fb29888" />
<img width="200" alt="5495caa2-7839-471a-a118-d6f2b34dcf30" src="https://github.com/user-attachments/assets/dd82b05d-b9a6-45b6-b24f-06149bb269d4" />
<img width="200"  alt="4a062d8d-ded1-4ba7-9254-4692ff19b0b2" src="https://github.com/user-attachments/assets/40226056-2800-4855-99a5-00c4397428e8" />
<img width="200"  alt="f444d87a-38b9-4bb5-9e22-f011b9d98244" src="https://github.com/user-attachments/assets/dc537f47-e7d0-47c6-8173-7d541f4709c0" />

Cấu trúc Thư mục (Folder Structure)
``\
MovieApp/
│
├── Models/
│   ├── Movie.swift             # Model chính (Hỗ trợ parse CodingKeys, custom URL)
│   └── MovieResponse.swift     # Wrapper hứng mảng dữ liệu từ API
│
├── Services/
│   └── MovieService.swift      # Xử lý URLSession async/await và bẫy lỗi HTTP
│
├── ViewModels/
│   ├── MovieListViewModel.swift # Quản lý state cho danh sách và tìm kiếm
│   └── FavoriteViewModel.swift  # Quản lý danh sách yêu thích toàn cục
│
├── Components/
│   ├── MovieCardView.swift     # Card hiển thị phim tái sử dụng (Dùng cho Home, Search, Fav)
│   └── RatingBadge.swift       # Badge điểm số đánh giá
│
├── Views/
│   ├── HomeView.swift          # Màn hình chính (Grid layout + Pull to refresh)
│   ├── SearchView.swift        # Màn hình tìm kiếm (Searchable)
│   ├── FavoriteView.swift      # Màn hình yêu thích
│   └── MovieDetailView.swift   # Màn hình thông tin chi tiết
│
└── MovieApp.swift              # App Entry Point (Thiết lập TabView & Environment)
``
