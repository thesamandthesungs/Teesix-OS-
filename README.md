# Teesix OS Interactive Core Preview Framework

Below is the live execution environment layout for the custom system platform.

<div style="background: #0b0b0e; display: flex; justify-content: center; align-items: center; padding: 40px 0; width: 100%;">
    
    <!-- 1. Mapped display aspect scaling for 1320 x 2868 pixels inside a hardware frame -->
    <div style="width: 396px; height: 860px; border: 14px solid #25252e; border-radius: 48px; position: relative; overflow: hidden; box-shadow: 0 25px 60px rgba(0,0,0,0.6); background-image: url('background.jpg'); background-size: cover; background-position: center; font-family: -apple-system, sans-serif;">
        
        <!-- 2. 120Hz Performance Interface Layout Layer -->
        <div style="height: 100%; display: flex; flex-direction: column; justify-content: space-between; padding: 16px; box-sizing: border-box;">
            
            <!-- Top Status Tracking Bar -->
            <div style="display: flex; justify-content: space-between; align-items: center; color: white; font-size: 11px; font-weight: 600; padding: 6px 14px; height: 20px;">
                <span>12:00</span>
                <span>📶 5G 🔋 100%</span>
            </div>

            <!-- Home Launcher Grid Layout -->
            <div style="display: grid; grid-template-columns: repeat(4, 1fr); gap: 16px; margin-top: 20px; padding: 0 10px;">
                <div style="display: flex; flex-direction: column; align-items: center; width: 100%;">
                    <img src="icons/phone-dialer.png" style="width: 64px; height: 64px; border-radius: 16px; object-fit: cover; box-shadow: 0 4px 12px rgba(0,0,0,0.4);" onerror="this.src='https://placehold.co'">
                    <div style="color: rgba(255,255,255,0.95); font-size: 11px; font-weight: 500; margin-top: 6px; text-shadow: 0 2px 4px rgba(0,0,0,0.6);">Phone</div>
                </div>
                <div style="display: flex; flex-direction: column; align-items: center; width: 100%;">
                    <img src="icons/system-settings.png" style="width: 64px; height: 64px; border-radius: 16px; object-fit: cover; box-shadow: 0 4px 12px rgba(0,0,0,0.4);" onerror="this.src='https://placehold.co'">
                    <div style="color: rgba(255,255,255,0.95); font-size: 11px; font-weight: 500; margin-top: 6px; text-shadow: 0 2px 4px rgba(0,0,0,0.6);">OS Config</div>
                </div>
            </div>

            <!-- 3. Bottom Persistent System Navigation Dock Layer -->
            <div style="background: rgba(255, 255, 255, 0.15); backdrop-filter: blur(25px); -webkit-backdrop-filter: blur(25px); border-radius: 28px; padding: 14px; margin-bottom: 8px; display: flex; justify-content: space-around; align-items: center; border: 1px solid rgba(255,255,255,0.1); box-shadow: 0 8px 32px rgba(0,0,0,0.3);">
                <!-- Pulls dock_icon.png from your main folder track -->
                <img src="dock_icon.png" style="width: 64px; height: 64px; border-radius: 16px; box-shadow: 0 4px 10px rgba(0,0,0,0.2);" onerror="this.src='https://placehold.co'">
            </div>
            
        </div>
    </div>
</div>
