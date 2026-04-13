import React from "react";

export default function UnikBDLanding() {
  return (
    <div className="min-h-screen bg-gray-50 text-gray-800">
      {/* Header */}
      <header className="bg-white shadow-md p-4 flex justify-between items-center">
        <h1 className="text-2xl font-bold text-green-600">UnikBD</h1>
        <div className="space-x-3">
          <a href="#products" className="px-4 py-2 bg-green-500 text-white rounded-2xl shadow">পণ্য দেখুন</a>
          <a href="#order" className="px-4 py-2 bg-blue-500 text-white rounded-2xl shadow">অর্ডার করুন</a>
          <a href="#contact" className="px-4 py-2 bg-gray-700 text-white rounded-2xl shadow">যোগাযোগ</a>
        </div>
      </header>

      {/* Hero Section */}
      <section className="text-center py-16 px-4">
        <h2 className="text-4xl font-bold mb-4">গরম ও বৃষ্টির জন্য সেরা সমাধান</h2>
        <p className="text-lg mb-6">উচ্চ মানের ছাতা ও রিচার্জেবল ফ্যান এখন আপনার হাতের নাগালে</p>
        <a href="#order" className="px-6 py-3 bg-green-600 text-white rounded-2xl shadow-lg">এখনই অর্ডার করুন</a>
      </section>

      {/* Products Section */}
      <section id="products" className="py-12 px-6">
        <h3 className="text-3xl font-semibold text-center mb-10">আমাদের পণ্য</h3>
        <div className="grid md:grid-cols-2 gap-8">
          {/* Umbrella */}
          <div className="bg-white p-6 rounded-2xl shadow">
            <img src="https://images.unsplash.com/photo-1523381210434-271e8be1f52b" alt="Umbrella" className="rounded-xl mb-4" />
            <h4 className="text-xl font-bold mb-2">প্রিমিয়াম ছাতা</h4>
            <p className="mb-2">✔️ মজবুত ফাইবার ফ্রেম
✔️ রোদ ও বৃষ্টি প্রতিরোধী
✔️ স্টাইলিশ ডিজাইন</p>
            <p className="font-semibold">৳ 750</p>
          </div>

          {/* Fan */}
          <div className="bg-white p-6 rounded-2xl shadow">
            <img src="https://images.unsplash.com/photo-1582719478250-c89cae4dc85b" alt="Fan" className="rounded-xl mb-4" />
            <h4 className="text-xl font-bold mb-2">রিচার্জেবল ফ্যান</h4>
            <p className="mb-2">✔️ দীর্ঘ সময় ব্যাটারি
✔️ USB চার্জিং
✔️ পোর্টেবল ডিজাইন</p>
            <p className="font-semibold">৳ 1200</p>
          </div>
        </div>
      </section>

      {/* Order Section */}
      <section id="order" className="py-12 px-6 bg-green-50 text-center">
        <h3 className="text-3xl font-semibold mb-6">অর্ডার করুন</h3>
        <p className="mb-4">অর্ডার করতে নিচের বাটনে ক্লিক করুন</p>
        <a
          href="https://wa.me/8801XXXXXXXXX?text=I want to order from UnikBD"
          className="px-6 py-3 bg-green-600 text-white rounded-2xl shadow-lg"
        >
          WhatsApp এ অর্ডার করুন
        </a>
      </section>

      {/* Contact Section */}
      <section id="contact" className="py-12 px-6 text-center">
        <h3 className="text-3xl font-semibold mb-4">যোগাযোগ</h3>
        <p>📞 Phone: 01XXXXXXXXX</p>
        <p>📍 Address: Bangladesh</p>
        <p>📧 Email: info@unikbd.com</p>
      </section>

      {/* Footer */}
      <footer className="bg-gray-800 text-white text-center p-4 mt-10">
        <p>© 2026 UnikBD. All rights reserved.</p>
      </footer>
    </div>
  );
}
