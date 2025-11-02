# css-life-pilot
:root {
    --primary-color: #2563eb;
    --primary-dark: #1d4ed8;
    --secondary-color: #10b981;
    --danger-color: #dc2626;
    --background-color: #f1f5f9;
    --card-background: white;
    --text-color: #1f2937;
    --border-color: #e5e7eb;
    --border-radius: 8px;
    --shadow-sm: 0 1px 2px rgba(0, 0, 0, 0.05);
    --shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1);
    --transition: all 0.3s ease;
}

/* Modern Form Styles */
.setup-form {
    max-width: 600px;
    margin: 0 auto;
}

.form-step {
    background: var(--card-background);
    padding: 2rem;
    border-radius: var(--border-radius);
    box-shadow: var(--shadow);
}

.form-step h3 {
    color: var(--primary-color);
    margin-bottom: 1.5rem;
    font-size: 1.5rem;
}

.form-group {
    margin-bottom: 1.5rem;
}

.form-group label {
    display: block;
    margin-bottom: 0.5rem;
    color: var(--text-color);
    font-weight: 500;
}

.form-group input,
.form-group select {
    width: 100%;
    padding: 0.75rem;
    border: 1px solid var(--border-color);
    border-radius: var(--border-radius);
    font-size: 1rem;
    transition: var(--transition);
}

.form-group input:focus,
.form-group select:focus {
    outline: none;
    border-color: var(--primary-color);
    box-shadow: 0 0 0 3px rgba(37, 99, 235, 0.1);
}

/* Dynamic Lists */
.dynamic-list {
    border: 1px solid var(--border-color);
    border-radius: var(--border-radius);
    padding: 1rem;
}

.input-group {
    display: flex;
    gap: 0.5rem;
    margin-bottom: 0.5rem;
}

.contact-group {
    display: grid;
    grid-template-columns: 1fr 1fr auto auto;
    gap: 0.5rem;
    margin-bottom: 0.5rem;
}

/* Buttons */
.next-btn,
.back-btn,
.submit-btn,
.add-btn {
    padding: 0.75rem 1.5rem;
    border: none;
    border-radius: var(--border-radius);
    font-weight: 500;
    cursor: pointer;
    transition: var(--transition);
    display: inline-flex;
    align-items: center;
    gap: 0.5rem;
}

.next-btn,
.submit-btn {
    background: var(--primary-color);
    color: white;
}

.next-btn:hover,
.submit-btn:hover {
    background: var(--primary-dark);
}

.back-btn {
    background: var(--border-color);
    color: var(--text-color);
}

.back-btn:hover {
    background: #d1d5db;
}

.add-btn {
    background: var(--secondary-color);
    color: white;
    padding: 0.5rem;
    border-radius: 50%;
}

.add-btn:hover {
    transform: scale(1.05);
}

/* Welcome Modal */
.welcome-modal {
    max-width: 700px;
    width: 90%;
}

.welcome-modal h2 {
    color: var(--primary-color);
    text-align: center;
    margin-bottom: 1rem;
}

.welcome-modal p {
    text-align: center;
    color: var(--text-color);
    margin-bottom: 2rem;
}

/* Form Navigation and Progress Indicators */
.form-navigation {
    margin-top: 2rem;
    text-align: center;
}

.progress-dots {
    display: flex;
    justify-content: center;
    gap: 1rem;
    margin-bottom: 1rem;
}

.dot {
    width: 12px;
    height: 12px;
    background-color: var(--border-color);
    border-radius: 50%;
    transition: all 0.3s ease;
}

.dot.active {
    background-color: var(--primary-color);
    transform: scale(1.2);
}

.progress-labels {
    display: flex;
    justify-content: center;
    gap: 2rem;
    font-size: 0.9rem;
    color: var(--text-color);
}

/* Save Confirmation Modal */
.success-modal {
    text-align: center;
    padding: 2rem;
}

.success-modal i {
    font-size: 4rem;
    color: var(--secondary-color);
    margin-bottom: 1rem;
}

.success-modal h2 {
    color: var(--text-color);
    margin-bottom: 1rem;
}

.confirm-btn {
    background: var(--secondary-color);
    color: white;
    border: none;
    border-radius: var(--border-radius);
    padding: 1rem 2rem;
    font-size: 1.1rem;
    cursor: pointer;
    margin-top: 1.5rem;
    transition: all 0.3s ease;
}

.confirm-btn:hover {
    background: #0d9668;
    transform: translateY(-2px);
}

/* Submit Button Enhancement */
.submit-btn {
    background: var(--secondary-color);
    color: white;
    padding: 1rem 2rem;
    font-size: 1.1rem;
    border: none;
    border-radius: var(--border-radius);
    cursor: pointer;
    transition: all 0.3s ease;
    display: inline-flex;
    align-items: center;
    gap: 0.5rem;
    margin-top: 1rem;
}

.submit-btn:hover {
    background: #0d9668;
    transform: translateY(-2px);
}

/* Dashboard Styles */
.profile-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 1rem;
    margin-bottom: 1rem;
}

.profile-item {
    background: #f8f9fa;
    padding: 1rem;
    border-radius: var(--border-radius);
}

.profile-item label {
    display: block;
    color: var(--text-color);
    font-size: 0.9rem;
    margin-bottom: 0.5rem;
}

.profile-item span {
    font-size: 1.1rem;
    font-weight: 500;
}

.medication-grid {
    display: grid;
    gap: 1rem;
    margin: 1rem 0;
}

.medication-item {
    display: flex;
    align-items: center;
    gap: 1rem;
    padding: 1rem;
    background: #f8f9fa;
    border-radius: var(--border-radius);
}

.medication-item i {
    color: var(--primary-color);
    font-size: 1.2rem;
}

.med-times {
    margin-left: auto;
    display: flex;
    gap: 1rem;
}

.time {
    font-size: 0.9rem;
    color: var(--text-color);
}

.contacts-grid {
    display: grid;
    gap: 1rem;
    margin: 1rem 0;
}

.contact-item {
    display: flex;
    align-items: center;
    gap: 1rem;
    padding: 1rem;
    background: #f8f9fa;
    border-radius: var(--border-radius);
}

.contact-info {
    display: flex;
    flex-direction: column;
}

.relation {
    font-size: 0.9rem;
    color: var(--text-color);
}

.reminders-list {
    list-style: none;
    padding: 0;
}

.reminders-list li {
    display: flex;
    align-items: center;
    gap: 0.5rem;
    padding: 0.5rem 0;
}

.edit-profile-btn,
.add-med-btn,
.add-contact-btn,
.update-metrics-btn {
    background: var(--primary-color);
    color: white;
    border: none;
    border-radius: var(--border-radius);
    padding: 0.5rem 1rem;
    cursor: pointer;
    display: flex;
    align-items: center;
    gap: 0.5rem;
    transition: var(--transition);
}

.edit-profile-btn:hover,
.add-med-btn:hover,
.add-contact-btn:hover,
.update-metrics-btn:hover {
    background: var(--primary-dark);
    transform: translateY(-2px);
}

.dashboard section.card {
    opacity: 0;
    transform: translateY(20px);
    animation: fadeInUp 0.5s forwards;
}

@keyframes fadeInUp {
    to {
        opacity: 1;
        transform: translateY(0);
    }
}

.dashboard section.card:nth-child(1) { animation-delay: 0.1s; }
.dashboard section.card:nth-child(2) { animation-delay: 0.2s; }
.dashboard section.card:nth-child(3) { animation-delay: 0.3s; }
.dashboard section.card:nth-child(4) { animation-delay: 0.4s; }
.dashboard section.card:nth-child(5) { animation-delay: 0.5s; }

body {
    margin: 0;
    font-family: 'Segoe UI', sans-serif;
    background: var(--background-color);
    color: var(--text-color);
    line-height: 1.6;
}

header {
    background: var(--primary-color);
    color: white;
    padding: 1rem;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

header h1 {
    margin: 0;
    font-size: 1.8rem;
}

nav {
    display: flex;
    gap: 1rem;
    margin-top: 1rem;
}

nav a {
    color: white;
    text-decoration: none;
    padding: 0.5rem 1rem;
    border-radius: var(--border-radius);
    transition: background-color 0.3s;
}

nav a:hover, nav a.active {
    background: rgba(255, 255, 255, 0.2);
}

.dashboard {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 1.5rem;
    padding: 1.5rem;
    max-width: 1400px;
    margin: 0 auto;
}

.card {
    background: var(--card-background);
    padding: 1.5rem;
    border-radius: var(--border-radius);
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

/* Profile Card */
.profile-card {
    grid-column: span 2;
}

#profile-info {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 1rem;
}

/* AI Assistant Section */
.ai-assistant {
    grid-column: span 2;
}

.assistant-options {
    display: flex;
    gap: 1rem;
    margin: 1rem 0;
    flex-wrap: wrap;
}

.ai-btn {
    display: flex;
    align-items: center;
    gap: 0.5rem;
    padding: 0.8rem 1.5rem;
    border: none;
    border-radius: var(--border-radius);
    background: var(--primary-color);
    color: white;
    cursor: pointer;
    transition: transform 0.2s;
}

.ai-btn:hover {
    transform: translateY(-2px);
}

.ai-response {
    background: #f8f9fa;
    padding: 1rem;
    border-radius: var(--border-radius);
    margin-top: 1rem;
}

/* Medications Section */
.medications {
    grid-column: span 2;
}

.medication-reminders {
    margin-top: 1rem;
    padding-top: 1rem;
    border-top: 1px solid #eee;
}

/* Emergency Section */
.emergency {
    grid-column: span 2;
}

.sos-button {
    width: 100%;
    padding: 1rem;
    background: var(--danger-color);
    color: white;
    border: none;
    border-radius: var(--border-radius);
    font-size: 1.2rem;
    font-weight: bold;
    cursor: pointer;
    margin: 1rem 0;
    transition: background-color 0.3s;
}

.sos-button:hover {
    background: #c0392b;
}

/* Health Metrics */
.metrics-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
    gap: 1rem;
}

.metric {
    text-align: center;
    padding: 1rem;
    background: #f8f9fa;
    border-radius: var(--border-radius);
}

/* Modal Styles */
.modal {
    display: none;
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: rgba(0, 0, 0, 0.5);
}

.modal-content {
    background: var(--card-background);
    margin: 10% auto;
    padding: 2rem;
    border-radius: var(--border-radius);
    max-width: 600px;
    position: relative;
}

.close {
    position: absolute;
    right: 1rem;
    top: 1rem;
    font-size: 1.5rem;
    cursor: pointer;
}

.emergency-modal {
    text-align: center;
}

#sos-confirm {
    width: 100%;
    padding: 0.5rem;
    margin: 1rem 0;
    border: 2px solid var(--danger-color);
    border-radius: var(--border-radius);
}

.modal-buttons {
    display: flex;
    gap: 1rem;
    justify-content: center;
    margin-top: 1rem;
}

.modal-buttons button {
    padding: 0.5rem 2rem;
    border: none;
    border-radius: var(--border-radius);
    cursor: pointer;
}

.modal-buttons button:first-child {
    background: var(--danger-color);
    color: white;
}

/* Responsive Design */
@media (max-width: 768px) {
    .dashboard {
        grid-template-columns: 1fr;
    }
    
    .profile-card,
    .ai-assistant,
    .medications,
    .emergency {
        grid-column: span 1;
    }
    
    .assistant-options {
        flex-direction: column;
    }
    
    .ai-btn {
        width: 100%;
    }
}
