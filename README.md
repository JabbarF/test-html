<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Informasi Sepatu</title>
    <!-- Tailwind CSS CDN for quick and responsive styling -->
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        /* Set global font for a modern look */
        body {
            font-family: "Inter", sans-serif;
            background-color: #f3f4f6; /* Light gray background color */
            display: flex; /* Use flexbox to center content */
            justify-content: center; /* Horizontally center content */
            align-items: center; /* Vertically center content */
            min-height: 100vh; /* Ensure minimum viewport height */
            margin: 0; /* Remove default body margin */
        }
        /* Styling for the main container */
        .container {
            max-width: 1024px; /* Maximum container width */
            margin-left: auto; /* Auto left margin */
            margin-right: auto; /* Auto right margin */
            padding: 1.5rem; /* Padding around the container */
            background-color: #ffffff; /* White background color */
            border-radius: 1rem; /* Rounded corners for the container */
            box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -2px rgba(0, 0, 0, 0.05); /* Soft shadow */
        }
        /* Styling for the product image */
        .product-image {
            width: 100%; /* Image width 100% of parent */
            height: auto; /* Auto height to maintain aspect ratio */
            border-radius: 0.75rem; /* Rounded corners for the image */
            margin-bottom: 1.5rem; /* Bottom margin for the image */
            box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1), 0 2px 4px -1px rgba(0, 0, 0, 0.06); /* Shadow for the image */
        }
        /* Styling for buttons */
        .buy-button {
            background-image: linear-gradient(to right, #6366f1, #8b5cf6); /* Blue to purple gradient */
            color: white; /* White text color */
            font-weight: bold; /* Bold text */
            padding: 0.75rem 2rem; /* Button padding */
            border-radius: 0.75rem; /* Rounded corners for the button */
            box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1), 0 2px 4px -1px rgba(0, 0, 0, 0.06); /* Button shadow */
            transition: transform 0.2s ease-in-out; /* Smooth transition on hover */
        }
        .buy-button:hover {
            transform: translateY(-2px); /* Slight lift effect on hover */
        }
        /* Styling for the table */
        .info-table {
            width: 100%; /* Table width 100% of parent */
            border-collapse: separate; /* Use separate border-collapse for border-radius */
            border-spacing: 0; /* Remove spacing between cells */
            margin-top: 2rem; /* Top margin for the table */
            border-radius: 0.75rem; /* Rounded corners for the table */
            overflow: hidden; /* Ensure rounded corners are applied correctly */
            box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1), 0 2px 4px -1px rgba(0, 0, 0, 0.06); /* Table shadow */
        }
        .info-table th, .info-table td {
            padding: 1rem 1.25rem; /* Padding inside table cells */
            text-align: left; /* Left-align text */
        }
        .info-table thead {
            background-color: #4f46e5; /* Table header background color */
            color: white; /* Table header text color */
        }
        .info-table tbody tr:nth-child(even) {
            background-color: #e0e7ff; /* Even row background color */
        }
        .info-table tbody tr:nth-child(odd) {
            background-color: #ffffff; /* Odd row background color */
        }
        .info-table tbody tr:hover {
            background-color: #bfdbfe; /* Hover background color for rows */
            transition: background-color 0.2s ease-in-out; /* Smooth transition */
        }
        /* Styling for small images in tables */
        .table-shoe-image {
            width: 50px; /* Small image width */
            height: auto; /* Auto height */
            border-radius: 0.25rem; /* Rounded corners */
            margin-right: 0.75rem; /* Right margin to separate from text */
            vertical-align: middle; /* Vertically align with text */
        }
    </style>
</head>
<body>
    <div class="container flex flex-col items-center">
        <!-- Main Product Information Section -->
        <img src="https://cdn.pixabay.com/photo/2016/11/19/18/06/feet-1840619_960_720.jpg"
             alt="Gambar Sepatu Asli"
             class="product-image"
             onerror="this.onerror=null;this.src='https://placehold.co/600x400/8b5cf6/ffffff?text=Gambar+Tidak+Tersedia';">
        
        <h2 class="text-3xl font-extrabold text-gray-900 mb-2 text-center">UltraFlex ComfortStride Edition</h2>
        <p class="text-2xl font-bold text-indigo-700 mb-6">Rp500.000</p>
        
        <button class="buy-button">Beli Sekarang</button>

        <!-- Shoe Information Table Section -->
        <h3 class="text-2xl font-bold text-gray-800 mt-10 mb-6">Informasi Detail Sepatu</h3>
        <table class="info-table">
            <thead>
                <tr>
                    <th>Nama</th>
                    <th>Harga</th>
                    <th>Stok</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>UltraFlex ComfortStride Edition</td>
                    <td>Rp500.000</td>
                    <td>25</td>
                </tr>
                <tr>
                    <td>AeroGlide PrecisionFit Pro Walk</td>
                    <td>Rp450.000</td>
                    <td>10</td>
                </tr>
                <tr>
                    <td>FusionFlow AdaptiveFit PrecisionStride</td>
                    <td>Rp650.000</td>
                    <td>15</td>
                </tr>
            </tbody>
        </table>
    </div>
</body>
</html>
