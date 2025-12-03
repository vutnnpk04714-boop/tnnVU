import React, { useState } from 'react';
import { Home, User, Code, Briefcase, Mail, Menu, X, Zap } from 'lucide-react';

// Dữ liệu mô phỏng
const data = {
  name: "Nguyễn Văn A",
  title: "Chuyên gia Lập trình & Phát triển Web",
  email: "van.a.dev@email.com",
  phone: "(+84) 901 234 567",
  github: "https://github.com/yourusername",
  linkedin: "https://linkedin.com/in/yourusername",
  about: "Tôi là một nhà phát triển web full-stack với hơn 5 năm kinh nghiệm, chuyên sâu về React, Node.js và kiến trúc microservices. Tôi đam mê xây dựng các ứng dụng hiệu suất cao, có khả năng mở rộng và mang lại trải nghiệm người dùng tuyệt vời. Tôi luôn tìm kiếm những thách thức mới và cơ hội để học hỏi các công nghệ tiên tiến.",
  skills: [
    { name: "React / Next.js", level: 95 },
    { name: "Node.js / Express", level: 90 },
    { name: "TypeScript / JavaScript", level: 90 },
    { name: "Tailwind CSS / SCSS", level: 85 },
    { name: "PostgreSQL / MongoDB", level: 80 },
    { name: "Docker / CI/CD", level: 75 },
  ],
  projects: [
    { title: "Ứng dụng Quản lý Dự án Đa Nền tảng", tech: "React Native, Node.js, GraphQL", description: "Phát triển một ứng dụng di động và web để theo dõi tiến độ công việc, phân công nhiệm vụ và báo cáo thời gian thực cho đội ngũ hơn 50 người." },
    { title: "Hệ thống E-commerce Hiệu suất Cao", tech: "Next.js, Tailwind CSS, Redis", description: "Tối ưu hóa tốc độ tải trang (dưới 1s) và xử lý hơn 10,000 giao dịch mỗi ngày. Tích hợp thanh toán và quản lý kho hàng tự động." },
    { title: "Công cụ Phân tích Dữ liệu Thời gian Thực", tech: "Python, Kafka, Dashboard React", description: "Xây dựng pipeline dữ liệu và giao diện trực quan hóa để phân tích hàng triệu điểm dữ liệu từ cảm biến IOT mỗi giờ." },
  ]
};

// Component Thanh điều hướng (Header)
const Navigation = ({ currentPage, setPage }) => {
  const [isMenuOpen, setIsMenuOpen] = useState(false);

  const navItems = [
    { name: "Trang chủ", icon: Home, page: 'home' },
    { name: "Thông tin", icon: User, page: 'about' },
    { name: "Kỹ năng", icon: Code, page: 'skills' },
    { name: "Dự án", icon: Briefcase, page: 'projects' },
    { name: "Liên hệ", icon: Mail, page: 'contact' },
  ];

  const NavLink = ({ item }) => (
    <button
      onClick={() => {
        setPage(item.page);
        setIsMenuOpen(false); // Đóng menu khi chọn (chỉ dành cho mobile)
      }}
      className={`
        flex items-center space-x-2 p-3 rounded-xl transition-all duration-300
        ${currentPage === item.page
          ? 'bg-indigo-600 text-white font-semibold shadow-lg shadow-indigo-500/50'
          : 'text-gray-700 hover:bg-indigo-50 hover:text-indigo-600'
        }
      `}
    >
      <item.icon size={20} />
      <span>{item.name}</span>
    </button>
  );

  return (
    <header className="fixed w-full bg-white shadow-xl z-50">
      <div className="container mx-auto px-4 sm:px-6 lg:px-8 py-3 flex justify-between items-center">
        {/* Logo/Tên */}
        <h1 className="text-2xl font-extrabold text-indigo-700 select-none">
          <Zap className="inline-block mr-1 h-6 w-6 text-yellow-500" />
          {data.name.split(' ').pop()} Portfolio
        </h1>

        {/* Menu Desktop */}
        <nav className="hidden md:flex space-x-2 lg:space-x-4">
          {navItems.map(item => (
            <NavLink key={item.page} item={item} />
          ))}
        </nav>

        {/* Nút Menu Mobile */}
        <button
          className="md:hidden p-2 rounded-lg text-gray-700 hover:bg-gray-100"
          onClick={() => setIsMenuOpen(!isMenuOpen)}
        >
          {isMenuOpen ? <X size={24} /> : <Menu size={24} />}
        </button>

        {/* Menu Mobile Drodown */}
        {isMenuOpen && (
          <div className="absolute top-full left-0 w-full bg-white shadow-lg md:hidden border-t border-gray-100 p-4">
            <nav className="flex flex-col space-y-2">
              {navItems.map(item => (
                <NavLink key={item.page} item={item} />
              ))}
            </nav>
          </div>
        )}
      </div>
    </header>
  );
};

// Component chung cho các phần nội dung
const Section = ({ title, id, children }) => (
  <section id={id} className="min-h-screen pt-24 pb-16 px-4 sm:px-6 lg:px-8 bg-gray-50">
    <div className="max-w-4xl mx-auto">
      <h2 className="text-4xl font-extrabold text-gray-900 mb-10 text-center border-b-4 border-indigo-500 pb-3">
        {title}
      </h2>
      {children}
    </div>
  </section>
);

// 1. Trang Chủ
const HomePage = () => (
  <Section id="home" title="Chào mừng">
    <div className="flex flex-col lg:flex-row items-center justify-between text-center lg:text-left bg-white p-8 rounded-2xl shadow-2xl">
      {/* Thông tin chính */}
      <div className="lg:w-2/3">
        <p className="text-xl text-indigo-600 font-semibold mb-2">Xin chào, tôi là</p>
        <h1 className="text-5xl md:text-6xl font-black text-gray-900 mb-4 leading-tight">
          {data.name}
        </h1>
        <p className="text-2xl text-gray-600 mb-6 font-light">
          {data.title}
        </p>
        <div className="flex justify-center lg:justify-start space-x-4">
          <a href="#contact" className="px-6 py-3 bg-indigo-600 text-white text-lg font-medium rounded-xl hover:bg-indigo-700 transition duration-300 shadow-md">
            Liên hệ ngay
          </a>
          <a href={data.github} target="_blank" rel="noopener noreferrer" className="px-6 py-3 border border-gray-300 text-gray-700 text-lg font-medium rounded-xl hover:bg-gray-100 transition duration-300">
            Xem GitHub
          </a>
        </div>
      </div>
      {/* Ảnh đại diện (Placeholder) */}
      <div className="lg:w-1/3 mt-8 lg:mt-0 flex justify-center">
        <div className="w-64 h-64 bg-gray-200 rounded-full shadow-xl flex items-center justify-center text-gray-500 text-sm overflow-hidden">
          {/* Thay thế bằng ảnh chân dung thực tế của bạn */}
          <User size={80} className="text-indigo-400" />
        </div>
      </div>
    </div>
  </Section>
);

// 2. Thông tin về bản thân
const AboutPage = () => (
  <Section id="about" title="Thông tin về bản thân">
    <div className="bg-white p-8 rounded-2xl shadow-xl text-lg text-gray-700 space-y-6">
      <p>{data.about}</p>
      <blockquote className="border-l-4 border-indigo-500 pl-4 italic text-gray-600">
        "Công nghệ thay đổi liên tục, và việc học hỏi không ngừng là chìa khóa để tạo ra những giải pháp đột phá."
      </blockquote>
      <div className="grid grid-cols-1 md:grid-cols-2 gap-4 pt-4 text-gray-800 font-medium">
        <p><Mail className="inline h-5 w-5 mr-2 text-indigo-500" />Email: <span className="font-normal">{data.email}</span></p>
        <p><Zap className="inline h-5 w-5 mr-2 text-indigo-500" />Chuyên môn: <span className="font-normal">Full-Stack Development</span></p>
        <p><Briefcase className="inline h-5 w-5 mr-2 text-indigo-500" />Kinh nghiệm: <span className="font-normal">5+ Năm</span></p>
        <p><Code className="inline h-5 w-5 mr-2 text-indigo-500" />Công nghệ ưa thích: <span className="font-normal">React, TypeScript, Node.js</span></p>
      </div>
    </div>
  </Section>
);

// 3. Kỹ năng
const SkillsPage = () => (
  <Section id="skills" title="Kỹ năng chuyên môn">
    <div className="grid grid-cols-1 md:grid-cols-2 gap-8">
      {data.skills.map((skill, index) => (
        <div key={index} className="bg-white p-6 rounded-xl shadow-lg hover:shadow-xl transition duration-300">
          <div className="flex justify-between items-center mb-2">
            <h3 className="text-xl font-semibold text-gray-800">{skill.name}</h3>
            <span className="text-indigo-600 font-bold">{skill.level}%</span>
          </div>
          <div className="w-full bg-gray-200 rounded-full h-2.5">
            <div
              className="bg-indigo-600 h-2.5 rounded-full transition-all duration-1000"
              style={{ width: `${skill.level}%` }}
            ></div>
          </div>
        </div>
      ))}
    </div>
    <div className="mt-10 text-center p-6 bg-indigo-50 rounded-xl text-indigo-800 font-medium">
        <p>Ngoài ra, tôi còn có kinh nghiệm làm việc với AWS, Google Cloud, và các phương pháp Agile/Scrum.</p>
    </div>
  </Section>
);

// 4. Dự án
const ProjectsPage = () => (
  <Section id="projects" title="Dự án nổi bật">
    <div className="space-y-10">
      {data.projects.map((project, index) => (
        <div key={index} className="bg-white p-8 rounded-2xl shadow-xl transition-transform transform hover:scale-[1.02] duration-300">
          <h3 className="text-2xl font-bold text-indigo-700 mb-3">{project.title}</h3>
          <p className="text-sm font-medium text-gray-500 mb-4 border-b pb-2">
            Công nghệ: <span className="font-semibold text-gray-700">{project.tech}</span>
          </p>
          <p className="text-gray-700 leading-relaxed">
            {project.description}
          </p>
          <div className="mt-5">
            <a href="#" className="text-indigo-600 font-medium hover:text-indigo-800 transition duration-150">
              Xem chi tiết <span aria-hidden="true">&rarr;</span>
            </a>
          </div>
        </div>
      ))}
    </div>
  </Section>
);

// 5. Liên hệ
const ContactPage = () => (
  <Section id="contact" title="Liên hệ với tôi">
    <div className="grid grid-cols-1 lg:grid-cols-2 gap-10">
      {/* Thông tin liên hệ */}
      <div className="bg-white p-8 rounded-2xl shadow-xl space-y-6">
        <h3 className="text-2xl font-bold text-gray-800 mb-4">Thông tin của tôi</h3>
        <div className="flex items-center space-x-3">
          <Mail className="h-6 w-6 text-indigo-500" />
          <span className="text-lg text-gray-700 font-medium">{data.email}</span>
        </div>
        <div className="flex items-center space-x-3">
          <Zap className="h-6 w-6 text-indigo-500" />
          <span className="text-lg text-gray-700 font-medium">{data.phone}</span>
        </div>
        
        <div className="pt-4 flex space-x-6">
            <a href={data.github} target="_blank" rel="noopener noreferrer" className="text-gray-500 hover:text-indigo-600 transition duration-300">
              {/* Sử dụng SVG icon cho GitHub - cần thêm icon nếu không có trong lucide-react */}
              <svg xmlns="http://www.w3.org/2000/svg" width="30" height="30" viewBox="0 0 24 24" fill="currentColor"><path d="M12 0c-6.626 0-12 5.373-12 12 0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.082-.742.083-.727.083-.727 1.205.084 1.839 1.237 1.839 1.237 1.07 1.833 2.807 1.304 3.492.997.107-.775.419-1.304.762-1.603-2.665-.305-5.467-1.334-5.467-5.931 0-1.312.469-2.387 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23.957-.266 1.983-.399 3.003-.404 1.02.005 2.046.138 3.003.404 2.293-1.552 3.301-1.23 3.301-1.23.653 1.652.242 2.873.117 3.176.766.834 1.235 1.909 1.235 3.221 0 4.609-2.807 5.624-5.474 5.921.432.37.823 1.107.823 2.222v3.293c0 .319.192.694.801.576C20.566 21.797 24 17.28 24 12c0-6.627-5.373-12-12-12z"/></svg>
            </a>
            <a href={data.linkedin} target="_blank" rel="noopener noreferrer" className="text-gray-500 hover:text-indigo-600 transition duration-300">
                {/* Sử dụng SVG icon cho LinkedIn */}
                <svg xmlns="http://www.w3.org/2000/svg" width="30" height="30" viewBox="0 0 24 24" fill="currentColor"><path d="M19 0h-14c-2.761 0-5 2.239-5 5v14c0 2.761 2.239 5 5 5h14c2.762 0 5-2.239 5-5v-14c0-2.761-2.238-5-5-5zm-11 19h-3v-11h3v11zm-1.5-12.268c-.966 0-1.75-.79-1.75-1.764s.784-1.764 1.75-1.764 1.75.79 1.75 1.764-.783 1.764-1.75 1.764zm13.5 12.268h-3v-5.604c0-3.368-4-3.535-4 0v5.604h-3v-11h3v1.765c1.396-2.586 7-2.777 7 2.476v6.759z"/></svg>
            </a>
        </div>
      </div>

      {/* Form Liên hệ */}
      <div className="bg-white p-8 rounded-2xl shadow-xl">
        <h3 className="text-2xl font-bold text-gray-800 mb-6">Gửi tin nhắn cho tôi</h3>
        <form className="space-y-4">
          <div>
            <label htmlFor="name" className="block text-sm font-medium text-gray-700 mb-1">Họ tên</label>
            <input
              type="text"
              id="name"
              className="w-full p-3 border border-gray-300 rounded-lg focus:ring-indigo-500 focus:border-indigo-500"
              placeholder="Tên của bạn"
              required
            />
          </div>
          <div>
            <label htmlFor="email" className="block text-sm font-medium text-gray-700 mb-1">Email</label>
            <input
              type="email"
              id="email"
              className="w-full p-3 border border-gray-300 rounded-lg focus:ring-indigo-500 focus:border-indigo-500"
              placeholder="email@vidu.com"
              required
            />
          </div>
          <div>
            <label htmlFor="message" className="block text-sm font-medium text-gray-700 mb-1">Tin nhắn</label>
            <textarea
              id="message"
              rows="4"
              className="w-full p-3 border border-gray-300 rounded-lg focus:ring-indigo-500 focus:border-indigo-500"
              placeholder="Bạn cần trao đổi về dự án hay cơ hội hợp tác nào?"
              required
            ></textarea>
          </div>
          <button
            type="submit"
            className="w-full py-3 bg-indigo-600 text-white font-semibold rounded-xl hover:bg-indigo-700 transition duration-300"
            onClick={(e) => {
              e.preventDefault(); // Ngăn chặn tải lại trang
              // Ở môi trường thực tế, bạn sẽ gửi dữ liệu form đến server tại đây.
              // Hiện tại, chỉ hiển thị thông báo mô phỏng:
              alert('Cảm ơn bạn! Tin nhắn của bạn đã được gửi. (Mô phỏng)');
            }}
          >
            Gửi Tin Nhắn
          </button>
        </form>
      </div>
    </div>
  </Section>
);

// Component Chân trang (Footer)
const Footer = () => (
  <footer className="bg-gray-800 text-white py-6 text-center">
    <p className="text-sm">
      &copy; {new Date().getFullYear()} {data.name}. Được xây dựng với React và Tailwind CSS.
    </p>
  </footer>
);

// Component Chính (App)
export default function App() {
  const [currentPage, setCurrentPage] = useState('home');

  const renderPage = () => {
    switch (currentPage) {
      case 'home':
        return <HomePage />;
      case 'about':
        return <AboutPage />;
      case 'skills':
        return <SkillsPage />;
      case 'projects':
        return <ProjectsPage />;
      case 'contact':
        return <ContactPage />;
      default:
        return <HomePage />;
    }
  };

  return (
    <div className="min-h-screen font-sans bg-gray-100">
      {/* Cấu hình Tailwind cho font Inter */}
      <style>{`
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@100..900&display=swap');
        body {
          font-family: 'Inter', sans-serif;
        }
      `}</style>
      
      {/* Thanh điều hướng */}
      <Navigation currentPage={currentPage} setPage={setCurrentPage} />

      {/* Nội dung chính */}
      <main className="pt-[68px] md:pt-[72px]">
        {renderPage()}
      </main>

      {/* Chân trang */}
      <Footer />
    </div>
  );
}
